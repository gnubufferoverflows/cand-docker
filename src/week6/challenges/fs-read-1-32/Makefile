all: fs-read-1-32

fs-read-1-32: fs-read-1-32.c
	cc -o $@ $< -m32 -DBUFSIZE=128 -O0 -no-pie -g

clean:
	rm -rf fs-read-1-32
