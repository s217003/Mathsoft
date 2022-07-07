roots : ./src/roots.c
	gcc -o ./bin/roots ./src/roots.c -I/home/lenovo/include/ -L/home/lenovo/lib/ -lgsl -lgslcblas
	./bin/roots > install.log
	mv install.log ./log

report :
	xelatex ./doc/report.tex
	rm report.aux
	rm report.log
	mv report.pdf ./doc

clear :
	rm ./bin/roots
	rm ./log/install.log
