#locate your libmysqlclient_r.so

all:
	gcc -g -O0 -Wall -o relayfetch relayfetch.c -I/usr/local/include/mysql/ -L/usr/local/lib/mysql -lmysqlclient_r -lpthread

clean:
	rm -rf *.o relayfetch
