# Cavity Analysis

This repository contains the LaTeX source for the Cavity Analysis document.

## Project Structure

- `Cavity.tex`: The main LaTeX document.
- `sections/`: This directory contains individual `.tex` files for each section of the document. Each section is included in the `Cavity.tex` file using `\input{}`.
- `figures/`: This directory contains all figures used in the document.
- `build/`: (Generated) This directory will contain the compiled PDF and other auxiliary files.

## Compilation Instructions

To compile the document, navigate to the root directory of this project and run the following command:

```bash
pdflatex Cavity.tex
```

You may need to run `pdflatex` multiple times to resolve all references (e.g., table of contents, figures).

If you have `latexmk` installed, you can simply run:

```bash
latexmk -pdf Cavity.tex
```

To clean up the generated files:

```bash
latexmk -c
```
