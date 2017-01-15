objects = test1.o test2.o
test : $(objects)
	mpicc -o test $(objects)
test1.o : test1.c
		mpicc -c test1.c
test2.o : test2.c
	gcc -c test2.c
clean:
	rm test $(objects)
