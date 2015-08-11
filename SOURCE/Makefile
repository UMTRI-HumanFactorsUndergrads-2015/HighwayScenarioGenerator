CC = g++
LD = g++

CFLAGS = -c -pedantic-errors -std=c++11 -Wall -fno-elide-constructors
LFLAGS = -pedantic -Wall

OBJS = main.o 
PROG = hsc_exe

default: $(PROG)

$(PROG): $(OBJS)
	$(LD) $(LFLAGS) $(OBJS) -o $(PROG)

main.o: main.cpp 
	$(CC) $(CFLAGS) main.cpp

clean:
	rm -f *.o

real_clean:
	rm -f *.o
	rm -f *exe

