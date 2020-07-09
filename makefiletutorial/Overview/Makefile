all: main.o
	@cc main.o -o main
main.o:main.c
	@cc -c main.c -o main.o
main.c:
	@echo "int main() { return 0; }" > main.c
clean:
	rm -f main.o main.c main