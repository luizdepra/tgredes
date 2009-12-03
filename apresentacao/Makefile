#Makefile
LATEX=pdflatex

#trabalho:
#	cd src && $(LATEX) trabalho.tex && $(LATEX) trabalho.tex
#	mv src/trabalho.pdf pdf/

slide:
	cd src && $(LATEX) slides.tex && $(LATEX) slides.tex
	mv src/slides.pdf pdf/

#all: trabalho slide
all: slide
	
clean:
	rm -f  src/*{.aux,.log,.toc,.nav,.out,.snm}
	rm -f pdf/*pdf
