CC=gcc
CFLAGS=-Wall -g
LIBS=-lcommons -lreadline
all: client
client: src/client.c
	$(CC) $(CFLAGS) -o client.out src/client.c $(LIBS)

clean:
	rm -rf client.out