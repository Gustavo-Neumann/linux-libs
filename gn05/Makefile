all:
	gcc -W -Wall -Wextra -pedantic -std=c17 -fPIC -c util.c -o util.o
	gcc -shared -fPIC -o libutil.so util.o	
	
	gcc -W -Wall -Wextra -std=c17 main.c -o gn05	
	

clean:
	rm -f main.o
	rm -f util.o
	rm -f libutil.so
	rm -f gn05
