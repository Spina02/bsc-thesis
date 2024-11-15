

## Overview
This repository contains the LaTeX files for my bachelor's degree thesis in computer engineering. The thesis focuses on aligning, denoising, and stacking lunar images using traditional techniques and unsharp masking based on deep learning.

The PDF to my BSc Thesis can be found [here](<https://raw.githubusercontent.com/Spina02/Thesis/main/src/Thesis.pdf>).

## Structure
- `src/Thesis.tex`: The main LaTeX file which compiles the entire thesis.
- `src/chapters/`: Directory containing individual chapter files.
- `src/references.bib`: Bibliography file with references used in the thesis.
- `assets/`: Directory for storing figures and images used in the thesis.

## Compilation
To compile the thesis, use the following command:
```
pdflatex -pdf Thesis.tex
```
Make sure to run the command multiple times to resolve all references and citations.

## Dependencies
- LaTeX distribution (e.g., TeX Live, MiKTeX)
- Bibliography tool (e.g., BibTeX, Biber)