CFLAGS= -Iinc


main: main.o file1.o file2.o
	gcc objs/main.o objs/file1.o objs/file2.o -o bin/main.out

main.o: src/main.c
	gcc -Iinc/ -c src/main.c -o objs/main.o

file1.o: src/file_1.c
	gcc -Iinc/ -c src/file_1.c -o objs/file1.o

file2.o: src/file_2.c
	gcc -Iinc/ -c src/file_2.c -o objs/file2.o

clean:
	rm objs/*
