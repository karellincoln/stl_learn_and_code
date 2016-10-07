template:main.o template.o 
	g++ template.o main.o -o template

main.o:main.cpp template.h
	g++ main.cpp template.h -c
template.o:template.cpp
	g++ template.cpp -c

clean:
	rm -f *.o template


