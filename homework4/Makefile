f0.bmp : test
	/home/lenovo/MathSoft/Mathsoft/homework4/bin/test f0.bmp -1.0 0.0 2.5
	mv f0.bmp /home/lenovo/MathSoft/Mathsoft/homework4/example/

test : /home/lenovo/MathSoft/Mathsoft/homework4/include/ /home/lenovo/MathSoft/Mathsoft/homework4/src/bitmap.cpp /home/lenovo/MathSoft/Mathsoft/homework4/src/manderbrot.cpp
	g++ -o test /home/lenovo/MathSoft/Mathsoft/homework4/src/manderbrot.cpp -I/home/lenovo/MathSoft/Mathsoft/homework4/include/ /home/lenovo/MathSoft/Mathsoft/homework4/src/bitmap.cpp
	mv test /home/lenovo/MathSoft/Mathsoft/homework4/bin/

clear :
	rm /home/lenovo/MathSoft/Mathsoft/homework4/example/f0.bmp
	rm /home/lenovo/MathSoft/Mathsoft/homework4/bin/test
