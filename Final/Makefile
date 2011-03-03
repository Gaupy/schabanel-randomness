all : main.pdf

main.pdf : main.tex 1.tex 2.tex 3.tex 4b-c.tex 4d.tex 5a.tex 6b-c.tex 6e.tex 6f.tex appendix1.tex
	latex main.tex
	bibtex main
	latex main.tex
	dvips main.dvi
	ps2pdf main.ps

clean:
	rm -f *.aux *.log *.pdfsync *.pdf *.toc *.blg *.bbl *.dvi *.ps
