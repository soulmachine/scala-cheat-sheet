Scala cheat sheet
============================

##Download PDF
[scala-cheat-sheet.pdf](https://github.com/soulmachine/scala-cheat-sheet/raw/master/scala-cheat-sheet.pdf) 

##How to compile on Windows
1. Install [Tex Live 2013](http://www.tug.org/texlive/), then add its `bin` path for example `D:\texlive\2013\bin\win32` to he PATH environment variable.
2. Install [TeXstudio](http://texstudio.sourceforge.net/).
3. Configure TeXstudio.  
    Run TeXstudio, click `Options-->Configure Texstudio-->Commands`, set `PdfLaTex` to `pdflatex.exe -synctex=1 -interaction=nonstopmode %.tex`.
    Click `Options-->Configure Texstudio-->Build`,   
    set `Build & View` to `Compile & View`,  
    set `Default Compiler` to `PdfLaTex`,  
    set `PDF Viewer` to `Internal PDF Viewer(windowed)`, so that when previewing it will pop up a standalone window, which will be convenient.
4. Compile. Open `scala-cheat-sheet.tex` with TeXstudio，click the green arrow on the menu bar, then it will start to compile.  
    In the messages window below we can see the compilation command that TeXstudio used is ` pdflatex.exe -synctex=1 -interaction=nonstopmode "scala-cheat-sheet".tex`
