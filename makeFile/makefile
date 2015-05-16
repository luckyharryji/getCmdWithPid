hello : hello.o
	gcc hello.o -o helloWorld
hello.o: hello.c
	gcc -c hello.c -o hello.o
.PHONY:clean
clean:
	rm -rf *.o helloWorld makefile~
