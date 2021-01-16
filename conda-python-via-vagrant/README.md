This document outlines how to install Python using conda under a Vagrant (virtual) environment.

To convert the `.md` markdown file to PDF, you will need [LaTeX](https://www.google.com/search?client=firefox-b-d&q=latex+download) and [pandoc](https://pandoc.org/). Then, do:

```bash
pandoc conda_python_via_vagrant.md --toc --number-sections --listings -H listings-setup.tex -V colorlinks --pdf-engine pdflatex -o conda_python_via_vagrant.pdf
```

