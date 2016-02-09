compile: generate-graphs
	pdflatex sdimitro-free-tier.tex
	bibtex sdimitro-free-tier
	pdflatex sdimitro-free-tier.tex
	pdflatex sdimitro-free-tier.tex

generate-graphs:
	gnuplot test.gpi

preview: compile
	evince sdimitro-free-tier.pdf

clean:
	rm -f *.pdf *.log *.aux *.png *.bbl *.blg
