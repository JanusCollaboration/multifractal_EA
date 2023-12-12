# Figures of the Supplemental Information for "Multifractality in spin glasses"

We provide the scripts and the data needed to reproduce the figures in the supplemental information in the article "Multifractality in spin glasses" (to appear in PNAS).

Each directory corresponds to one figure. In each directory `figS??/`, you will find:

1. A gnuplot (.gpt) script of the figure.
2. A directory "data" with all the needed data for the figure.
3. A "data_information.txt" where the data files are explained.
4. A .pdf with the produced figure.

To run the scripts, you need the Version 5.2 of Gnuplot and the `pdflatex` compiler. Inside the directory of any figure (figure 1, for instance), do
```
gnuplot figS1.gpt ; pdflatex figS1.tex
```
The corresponding figS1.pdf will be produced in that directory. The same procedure works for the other figures by changing figS1.gpt and figS1.tex as appropriate. 
