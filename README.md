# Amir Hossein Daraie's Resume Files 

This repository contains the files associated with my resume. I built my resume with LaTeX using a default template. It was very helpful and allowed me to make a very beautiful resume for myself. I am sharing it here in GitHub for two main reasons:

1. There we many requests and questions about how I made my resume. I am sharing the files here so *my friends can use it as a template for themselves*.
2. I can track the changes over time and keep track of everything that is happening in the LaTeX code associated with it.

Hope you find it useful! 🤓

## My CV in LaTeX

The resume typesetting is done in XeLaTeX.

## Output File
Note that the final file will be in the build folder named: **_CV.pdf_**

## Requirements
* Up to date TeX distribution like TexLive

## How to Compile
Run the following command in a terminal:

`xelatex -synctex=1 -shell-escape --output-directory=build -interaction=nonstopmode  CV.tex`
