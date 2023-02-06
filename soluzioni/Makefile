# LaTeX Makefile
FILE=main

all: $(FILE).pdf

.PHONY: clean $(FILE).pdf

clean:
	rm -f *.aux
	rm -f *.auxlock
	rm -f *.bak
	rm -f *.bbl
	rm -f *.blg
	rm -f *.brf
	rm -f *.dep
	rm -f *.dvi
	rm -f *.gz
	rm -f *.idx
	rm -f *.ilg
	rm -f *.ind
	rm -f *.loa
	rm -f *.lof
	rm -f *.log
	rm -f *.lot
	rm -f *.mat
	rm -f *.nav
	rm -f *.out
	rm -f *.pdfsync
	rm -f *.ps
	rm -f *.snm
	rm -f *.spl
	rm -f *.thm
	rm -f *.toc
	rm -f ${FILE}.pdf


$(FILE).pdf: $(FILE).tex
	pdflatex $(FILE).tex
	-bibtex $(FILE).aux
	-makeindex $(FILE).idx
	pdflatex $(FILE).tex
	pdflatex $(FILE).tex
	rm -f *.aux
	rm -f *.auxlock
	rm -f *.bak
	rm -f *.bbl
	rm -f *.blg
	rm -f *.brf
	rm -f *.dep
	rm -f *.dvi
	rm -f *.gz
	rm -f *.idx
	rm -f *.ilg
	rm -f *.ind
	rm -f *.loa
	rm -f *.lof
	rm -f *.log
	rm -f *.lot
	rm -f *.mat
	rm -f *.nav
	rm -f *.out
	rm -f *.pdfsync
	rm -f *.ps
	rm -f *.snm
	rm -f *.spl
	rm -f *.thm
	rm -f *.toc
