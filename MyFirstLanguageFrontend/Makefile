
all:
	clang++ -O3 -g toy.cpp -o toy $(shell llvm-config --cxxflags) -std=c++14 $(shell llvm-config --ldflags --libs) -lpthread -ltinfo
