TEX = pdflatex
#BIBTEX = bibtex
PDF = basic_results.pdf
SRC = *.tex Makefile

default: $(PDF)

$(PDF): $(SRC)
	$(TEX) basic_results.tex
	$(TEX) basic_results.tex
	$(TEX) basic_results.tex
	$(TEX) translate_input.tex
	$(TEX) translate_input.tex
	$(TEX) translate_input.tex
	$(TEX) transducer_complexity.tex
	$(TEX) transducer_complexity.tex
	$(TEX) transducer_complexity.tex
clean:
	rm *.aux *.log *.toc *.lof *.lot *.blg
