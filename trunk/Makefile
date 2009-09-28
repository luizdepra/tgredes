# 2 pdflatex are necessary for making the cross references
tg.pdf: tg.tex
	pdflatex tg.tex
	pdflatex tg.tex
# opens the manual with this parameter
all: tg.pdf
	evince tg.pdf
# clears all the auxiliar files generated during the process
clean:
	rm *.aux *.idx *.log *.out *.toc *.pdf  2> /dev/null
