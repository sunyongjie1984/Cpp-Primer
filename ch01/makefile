# in ex1_9 auto as return type c++11 is not allowed
#CFLAGS = -g -Wall -std=c++11
CFLAGS = -g -Wall -std=c++14

all : ex1_1 ex1_9

#all : ex1_1 ex1_9 ex1_10  ex1_11  ex1_16  ex1_20  ex1_21  ex1_22  ex1_23
ex1_1 : ex1_1.cpp
	g++ -o ex1_1 ${CFLAGS} ex1_1.cpp
ex1_9 : ex1_9.cpp
	g++ -o ex1_9 ${CFLAGS} ex1_9.cpp
clean :
	rm -rf *.o ex1_1 ex1_9 ex1_10  ex1_11  ex1_16  ex1_20  ex1_21  ex1_22  ex1_23 *.dSYM
