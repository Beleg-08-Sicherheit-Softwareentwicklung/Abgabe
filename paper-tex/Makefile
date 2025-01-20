buildlatex=pdflatex -shell-escape

all:
	$(buildlatex) 08-Security-Software.tex
	bibtex 08-Security-Software
	$(buildlatex) 08-Security-Software.tex
	$(buildlatex) 08-Security-Software.tex