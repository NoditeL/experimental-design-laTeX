# Experimental Design LaTeX Report

This repository contains a LaTeX project for a report on experimental design, analysis of variance (ANOVA), and multiple comparisons.

## Contents

- `main.tex` – The LaTeX source file with sections on experimental design, ANOVA, and multiple comparisons.
- `references.bib` – Bibliographic database used to compile the report.
- `main.pdf` – A compiled PDF version of the report generated in this session.
- `Makefile` – A simple Makefile that builds the PDF using `pdflatex` and `bibtex`.

## Building

To compile the LaTeX document yourself, make sure you have a working LaTeX distribution (e.g., TeX Live) installed. Then run:

```bash
make
```

This will generate `main.pdf` in the project directory.

You can clean up auxiliary build files with:

```bash
make clean
```
