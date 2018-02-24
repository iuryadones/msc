# Msc

Gerar o arquivo em PDF

```bash
$ pdflatex -synctex=1 -interaction=nonstopmode projeto_pesquisa.tex
$ bibtex projeto_pesquisa.aux
$ pdflatex -synctex=1 -interaction=nonstopmode projeto_pesquisa.tex
$ pdflatex -synctex=1 -interaction=nonstopmode projeto_pesquisa.tex
```