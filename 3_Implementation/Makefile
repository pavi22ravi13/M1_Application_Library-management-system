output: main.o 
	g++ main.o -o output

main.o: Main/main.c 
	g++ -c Main/main.c
clean:
	rm *.o output


SRC = Main/main.c
PROJECT_OUTPUT = $(PROJECT_NAME).out 
all: $(SRC) $(BUILD)
	g++ $(SRC) -o $(PROJECT_OUTPUT)