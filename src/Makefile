MY_STATIC = -static

helloworld : helloworld.o
	$(CC) $(LDFLAGS)  $(MY_STATIC) helloworld.o -o helloworld

helloworld.o : helloworld.c
	$(CC) $(CFLAGS) -c helloworld.c

clean :
		rm *.o helloworld
