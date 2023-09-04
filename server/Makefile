CC=gcc
CFLAGS=-Wall -g
LIBS=-lcommons -lreadline
all: server
server: src/server.c
	$(CC) $(CFLAGS) -o server.out src/server.c $(LIBS)

clean:
	rm -rf server.out