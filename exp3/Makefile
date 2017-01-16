CC = gcc
INC = -I ./include

test: main.o op.o
	 $(CC) -o $@ main.o op.o
%.o: %.c
	 ${CC} $< ${INC} -c 
clean:
	rm -f test main.o op.o	
