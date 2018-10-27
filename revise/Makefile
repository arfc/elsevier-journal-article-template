NAME=revise
AUX=$(NAME).aux
INTERMEDIATES=$(NAME).bbl $(NAME).blg $(NAME).log

all: $(NAME).pdf

$(NAME).pdf : $(NAME).tex
	pdflatex -shell-escape $(NAME)
	bibtex $(NAME)
	pdflatex -shell-escape $(NAME)
	pdflatex -shell-escape $(NAME)

clean :
	rm $(AUX) $(INTERMEDIATES) $(NAME).pdf
