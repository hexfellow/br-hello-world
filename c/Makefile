CC = gcc
CFLAGS = -Wall -Wextra -O2
TARGET = hello-world-c
SRC = main.c

.PHONY: all clean

all: $(TARGET)

$(TARGET): $(SRC)
	$(CC) $(CFLAGS) -o $(TARGET) $(SRC)

clean:
	rm -f $(TARGET)
