CC := g++  
CFLAGS := -g   -std=c++11
TARGET := bchain
SRCS := $(wildcard *.cpp)  
OBJS := $(patsubst %cpp,%o,$(SRCS))  
all:$(TARGET)  
%.o:%.cpp  
	$(CC) $(CFLAGS) -c $<  
$(TARGET):$(OBJS)  
	$(CC) $(CFLAGS) -o $@ $^  
clean:  
	rm -rf $(TARGET) *.o 

