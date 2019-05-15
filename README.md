# Beamer template for Boston University

This is a `beamer` template for creating presentation slides for Boston University. The template is built on top of `metropolis` theme, with the color theme modified.

The file `main.tex` include a simple example, along with the sample pdf shown in `example.pdf`.

You need to have LaTeX installed on your system. To compile the PDF file along with the references, use the following command line on Linux/macOS:

```
pdflatex main && bibtex main && pdflatex main && pdflatex main
```

where `main` is the main TeX file i.e. `main.tex`
