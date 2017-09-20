all:	temperv14

CFLAGS = -O2 -Wall

temperv14:	temperv14.c
	${CC} -DUNIT_TEST -o $@ $^ -lusb

clean:		
	rm -f temperv14 *.o
