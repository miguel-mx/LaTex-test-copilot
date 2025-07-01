# LaTeX Example with GitHub Actions

This repository demonstrates how to automatically compile a LaTeX document (`main.tex`) and publish the resulting PDF to the repository using GitHub Actions.

## How it works

- On every push to the `main` branch, the workflow:
  1. Compiles `main.tex` using `pdflatex`.
  2. Saves the output PDF in the `/output` directory.
  3. Commits and pushes the PDF (`output/main.pdf`) back to the repository.

## Usage

- Edit `main.tex` as needed.
- When you push changes, `output/main.pdf` will be updated automatically.

## Workflow file

See [`.github/workflows/latex.yml`](.github/workflows/latex.yml) for details.
