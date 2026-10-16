# Research Proposal: Rice Pollen Viability Classification

## Requirements

Install [MiKTeX](https://miktex.org/) or [TeX Live](https://tug.org/texlive/).

## Build

From the project folder, run:

```
latexmk -pdf main.tex
```

This produces `main.pdf`.

To build manually instead:

```
pdflatex main.tex
biber main
pdflatex main.tex
pdflatex main.tex
```

In VS Code, install the **LaTeX Workshop** extension and build with the **latexmk** recipe.
