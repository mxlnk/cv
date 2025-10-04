# Resume
[![build](https://github.com/Germandrummer92/resume/actions/workflows/main.yml/badge.svg)](https://github.com/Germandrummer92/resume/actions/workflows/main.yml)

Personal LaTeX resume based on [latextemplates.com template](https://www.latextemplates.com/template/developer-cv).

## Compiling locally

Make sure you have texlive installed:

linux
```bash
sudo apt-get update &&
sudo apt-get install -y --no-install-recommends texlive-latex-base texlive-fonts-recommended texlive-fonts-extra texlive-latex-extra
```

macos
```bash
brew install texlive
```

then build using pdflatex:

```bash
pdflatex main.tex
```

## Github action

Automatically builds a resume.pdf as a [github action](./.github/workflows/main.yml). 

Latest resume available as an artifact from the latest [action run](https://github.com/Germandrummer92/resume/actions/workflows/main.yml).

## Preview

![preview of the output resume](preview.png "preview of the output")


