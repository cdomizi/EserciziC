all:libmath

libmath.so : quiz.o
	gcc -shared -o libmath.so quiz.o

quiz.o : quiz.h
	gcc -o quiz.o quiz.c
