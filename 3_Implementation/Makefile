output: main.o library.o
	g++ main.o library.o -o output

main.o: Main/main.c 
	g++ -c Main/main.c

library.o: src/library.c
	g++ -c src/library.c

clean:
	rm *.o output
