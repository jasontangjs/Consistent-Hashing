LIB = ../lib
objects = ConsistentHash.o md5.o MD5HashFunc.o Node.o
		
all: $(objects)

#�� *.o �ŵ�./libs��
%.o: %.cpp
	g++ -std=c++11 -c $< -o $(LIB)/$@  

.PHONY: clean
clean:
	-rm $(LIB)/ConsistentHash.o $(LIB)/md5.o $(LIB)/MD5HashFunc.o $(LIB)/Node.o