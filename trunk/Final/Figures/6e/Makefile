all : 6e5.pdf

main.pdf : 6e5.tex
	latex 6e5.tex
	dvips 6e5.dvi
	ps2epsi 6e5.ps
	epstopdf 6e5.epsi


clean:
	rm -f *.aux *.log *.pdfsync *.pdf *.toc *.blg *.bbl *.dvi *.ps *dvi *epsi
