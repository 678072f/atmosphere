all: hello

hello: hello.o
	g++ -o hello hello.o

hello.o: hello.c
	g++ -c hello.c

clean:
	rm -rf *.o
