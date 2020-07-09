.DEFAULT_GOAL := generate

say_hello:
	@echo "Hello world"

generate:
	@echo "Creating empty text file..."
	touch file-{1..10}.txt
	@echo "File was created"
clean:
	@echo "Clean up file ..."
	rm *.txt

all: say_hello generate
