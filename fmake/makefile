res : main.o 1.o 2.o	
	gcc main.o 1.o 2.o
1.o : 1.c 1.h
	gcc -c 1.c 
2.o : 2.c 2.h
	gcc -c 2.c
main.o : main.c 1.o 2.o
	gcc -c main.c 
