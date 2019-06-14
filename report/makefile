SHELL = /bin/sh
.SUFFIXES:
.SUFFIXES: .tex .pdf .bib
out/m2r-report.pdf: *.tex ref.bib
	latexmk -interaction=nonstopmode
