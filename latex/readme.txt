Para compilar latex e transforma-lo em pdf:

- pdflatex thiagogtMonografia.tex (gera o .aux necessario para indexar as referencias)

- bibtex thiagogtMonografia.aux (gera as referencias no .aux)

- pdflatex thiagogtMonografia.tex (gera o pdf correto)

