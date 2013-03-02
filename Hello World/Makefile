

GCC = gcc
CFLAGS = -Wall

SRCS = Hello_World.c
OBJS = Hello_World.o
TARGET = Hello_World


all :
	$(TARGET)

$(TARGET) : $(OBJS)
	$(GCC) $(SRCS) -o $@

%.o : %.c
	$(GCC) -c $(CFLAGS) $^