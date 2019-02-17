.PHONY: all

all: hello

hello: hello.cpp
	g++ -o hello hello.cpp

.PHONY: install

install:
	mkdir -p bin
	cp hello bin/

.PHONY: clean
clean:
	rm -rf hello



