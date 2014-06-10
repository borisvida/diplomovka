TEX = pdflatex
#BIBTEX = bibtex
PDF = main.pdf
SRC = *.tex Makefile

default: $(PDF)

$(PDF): $(SRC)
	$(TEX) main.tex
#	$(BIBTEX) main
	$(TEX) main.tex
	$(TEX) main.tex

clean:
	rm *.aux *.log *.toc *.lof *.lot *.blg
