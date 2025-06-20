# 8833_Adv_Web_A2

## Compile environment
This project relies on latex, it configured depend on VSCode.
The extension is **LateX Workshop**
The editor depended command tool is [TeX Live](https://www.tug.org/texlive/)

## Compile process
When user saving any tex file, the editor will compile this project automatically.
The output files will generated in **output** folder, if error happen, create it manually.
The citation data stored in *.bib* files, it can cause compile errors if it including chars like &, try to change it to \&, and delete the "main.bbl" file in output folder, then compiling again by saving any tex file.