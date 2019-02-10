MAIN = demo.cpp
EXEC = demo
CC = g++

CFLAGS = `pkg-config --cflags opencv` `pkg-config --libs opencv`

main:  
	$(CC)  $(MAIN)  -o $(EXEC) $(CFLAGS) -g -Wall 

clean:
	rm $(EXEC) -rf


