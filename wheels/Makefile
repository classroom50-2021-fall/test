tests:
	clang -ggdb3 -std=c11 -Wno-incompatible-library-redeclaration -c -o ctype.o ctype.c
	clang -ggdb3 -std=c11 -Wno-incompatible-library-redeclaration -c -o tests.o tests.c
	clang -ggdb3 -std=c11 -o tests ctype.o tests.o
