all: main.tex
	xelatex main.tex

zip: main.tex
	zip beamer-bupt.zip main.tex Makefile bupt-logo.pdf

clean:
	-rm -f *.aux *.log *.nav *.out *.pdf *.snm *.toc