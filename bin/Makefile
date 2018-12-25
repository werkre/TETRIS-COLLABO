IDIR =../include
ODIR=../src
CXX=g++ 
CFLAGS= -I$(IDIR) -std=c++11 -g


OBJ=

all: $(OBJ)
	$(CXX) $(OBJ) -o TETRIS

main.o:	$(ODIR)/main.cpp
	$(CXX) -c -o $@ $< $(CFLAGS)

clean:
	rd TETRIS.exe
	rd *.o
