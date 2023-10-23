CC = gcc
SRC = src/
CFLAGS = -g -fno-omit-frame-pointer -Ofast -mavx -ffast-math -march=native

.DEFAULT_GOAL = MD.exe

MD.exe: $(SRC)/MD.cpp
	$(CC) $(CFLAGS) $(SRC)MD.cpp -lm -o MD.exe

clean:
	rm ./MD.exe

run:
	./MD.exe < inputdata.txt
