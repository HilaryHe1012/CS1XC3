CC=gcc

# Assigning all to the string main
all: main 

# Compile main.c using both the course and student library
main: course.o student.o

course.o: student.o

# Clean all the files generated by the make all command by running make clean
clean:
	rm -f -r *.o main

