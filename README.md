# pdfinspector


A quick app that takes a directory of PDFs (or a single PDF) and lists out info about each PDF that may make it harder to archive.  This includes
* Embedded Files
* Layers
* Forms

`git pull ; mvn clean compile -Pinspect  -Dexec.args="/{path-to-pdfs}/" > ~/pdfstats.txt `
