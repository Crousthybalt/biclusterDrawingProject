all:
	pdflatex -interaction=nonstopmode -file-line-error main.tex

	bibtex main references referencesAbstract
	pdflatex -interaction=nonstopmode -file-line-error main.tex
	pdflatex -interaction=nonstopmode -file-line-error main.tex
