pdf:
	pdflatex TP_copy.tex

ignorando-errores:
	pdflatex -interaction=nonstopmode TP_copy.tex

bibliografia:
	pdflatex TP_copy.tex
	bibtex TP_copy.aux
	pdflatex TP_copy.tex
	pdflatex TP_copy.tex

clean:
	- rm -f *.log *.soc *.toc *.aux *.out  main.idx *.bbl *.bbg *.dvi *.blg *.lof *.nav *.snm *~

