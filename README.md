# Resume LaTeX Template

This repository contains the source files of my cv using LaTeX, specifically designed to be compiled with XeLaTeX.  
This is based on the template provided by:  
- Xavier Danaux (xdanaux@gmail.com) and Vel (vel@latextemplates.com)
- http://www.LaTeXTemplates.com

## Requirements

- **TeX Distribution**: An up-to-date TeX distribution, such as **TeX Live**.
- **XeLaTeX**: This resume is typeset using **XeLaTeX** for better font and Unicode support.

## Compilation Instructions

To compile the resume, use the following command in your terminal:

```bash
xelatex -synctex=1 -shell-escape --output-directory=build -interaction=nonstopmode CV.tex

