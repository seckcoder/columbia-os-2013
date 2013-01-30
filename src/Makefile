OPTIMIZATION?=-O0

STD= -std=c99 -pedantic
WARN= -Wall
OPT= $(OPTIMIZATION)
DEBUG= -g
CC=gcc

E01= myshell
E01_OBJ= myshell.o

CFLAGS= $(STD) $(WARN) $(OPT) $(DEBUG)

all: $(E01)


.PHONY: all

$(E01): $(E01_OBJ)
	$(CC) $^ $(CFLAGS) -o $@

.PHONY: clean
clean:
	-rm -f *.o $(E01)
