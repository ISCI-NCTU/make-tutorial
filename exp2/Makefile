OBJ = main.o op.o
test: main.o op.o
	 cc main.o op.o -o test
main.o: main.c
	 cc -c main.c
op.o: op.c
clean:
		rm -f test ${OBJ} 
