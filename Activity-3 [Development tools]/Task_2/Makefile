all:bitmask.o myutils.o test.o mystring.o 
	gcc bitmask.o myutils.o test.o mystring.o -o all.out

bitmask.o:
	gcc -c src/bitmask.c

myutils.o:
	gcc -c src/myutils.c

test.o:
	gcc -c test.c

mystring.o:
	gcc -c src/mystring.c

clean:
	rm -rf *.o *.out
