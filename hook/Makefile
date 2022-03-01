reporting-io.so: reporting-io.c
	gcc -shared -fPIC reporting-io.c -o $@ -ldl

all: reporting-io.so

.PHONY: all