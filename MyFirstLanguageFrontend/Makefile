
all:
	clang++-7 -O3 -g toy.cpp -o toy $(shell llvm-config-7 --cxxflags) -std=c++14 $(shell llvm-config-7 --ldflags --libs) -lpthread -ltinfo
