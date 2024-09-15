pdf:
	pdflatex TP.tex

ignorando-errores:
	pdflatex -interaction=nonstopmode TP.tex

bibliografia:
	pdflatex TP.tex
	bibtex ejemplo_tp_grupal.aux
	pdflatex TP.tex
	pdflatex TP.tex

clean:
	- rm -f *.log *.soc *.toc *.aux *.out  main.idx *.bbl *.bbg *.dvi *.blg *.lof *.nav *.snm *~

