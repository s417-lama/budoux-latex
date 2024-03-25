FILENAME=example

pdf: $(FILENAME).tex
	cp -f $(FILENAME).tex $(FILENAME).mid.tex
	latexmk -lualatex --shell-escape $(FILENAME).mid.tex
	cp -f $(FILENAME).mid.pdf $(FILENAME).pdf

clean:
	rm -f $(FILENAME).mid*
