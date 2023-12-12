# Figures of "Multifractality in spin glasses"

The scripts and the data needed to reproduce the figures on the article
"Multifractality in spin glasses" (https://arxiv.org/abs/2306.04591) are
provided. Folder `MAIN/` contains the figures and data corresponding to the
main article, while `SI/` has the figures and data for the supplemental
information.

Inside `MAIN/` and `SI/`, each directory corresponds to one figure. In
each directory `fig??/` you can find:

1. A gnuplot (.gpt) script of the figure.
2. A directory "data" with all the needed data for the figure.
3. A "data_information.txt" where the data files are explained.
4. A .pdf with the produced figure.

For running the scripts you need the Version 5.2 of Gnuplot and the pdflatex compiler. Inside the directory of any figure you can simply do

gnuplot fig1.gpt ; pdflatex fig1.tex

The corresponding fig1.pdf will be produced in that directory.
