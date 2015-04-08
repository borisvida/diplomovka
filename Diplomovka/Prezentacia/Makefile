TEX = pdflatex
BIBTEX = bibtex
PDF = main.pdf
SRC = *.tex

default: $(PDF)

$(PDF): $(SRC)
	$(TEX) main.tex
	$(BIBTEX) main
	$(TEX) main.tex
	$(TEX) main.tex

clean:
	rm *.aux *.log *.toc *.lof *.lot *.bbl *.blg
