program: main.o funcs.o TrianglePrinter.o
	g++ main.o funcs.o TrianglePrinter -o program
main.o: main.cpp funcs.h TrianglePrinter.h
	g++ -c main.cpp
funcs.o: funcs.cpp funcs.h
	g++ -c funcs.cpp
TrianglePrinter.o: TrianglePrinter.cpp TrianglePrinter.h
	g++ -c TrianglePrinter.cpp
.PHONY: clean

clean: 
	-@rm -f program
	-@rm -f *.o
