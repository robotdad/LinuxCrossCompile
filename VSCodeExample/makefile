all: hello

hello: hello.o
	arm-linux-gnueabihf-g++ -o "hello" hello.o

hello.o: main.cpp
	arm-linux-gnueabihf-g++ -O3 -g3 -Wall -c -fPIC -o "hello.o" "main.cpp"

clean:
	rm *.o hello
