default: solution
	./solution

solution: main.c sum.o
	gcc main.c sum.o -o solution

sum.o: lib/sum.h lib/sum.c
	gcc -c lib/sum.c