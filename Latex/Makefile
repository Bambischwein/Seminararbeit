CC = pdflatex
CFLAGS = --shell-escape
all:llncs.pdf

llncs.pdf:llncs.tex
	$(CC) $(CCFLAGS) $^
	$(CC) $(CCFLAGS) $^
clean:
	rm -rf *.aux
	rm -rf *.pdf
	rm -rf *.log
	rm -rf *.toc

.PHONY:clean

