

LABS := lab1.pdf lab2.pdf lab3.pdf lab4.pdf lab5.pdf lab6.pdf lab7.pdf lab8.pdf

all: $(LABS) FAQ.pdf

.PHONY := all

%.pdf: %.md
	pandoc -t latex -o $@ $<


