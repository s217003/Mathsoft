result.txt : test1 test2
	./test1 > result.dat
	./test2 >> result.dat

test1 : roots_bisection.c
	gcc -o test1 roots_bisection.c -I /home/lenovo/include/ -L /home/lenovo/lib/ -lgsl -lgslcblas 

test2 : roots_newton.c
	gcc -o test2 roots_newton.c -I /home/lenovo/include/ -L /home/lenovo/lib/ -lgsl -lgslcblas 

clear :
	rm test1
	rm test2
	rm result.dat
