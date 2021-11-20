# all: httpd client
# LIBS = -lpthread #-lsocket
# httpd: httpd.c
# 	gcc -g -W -Wall  $(LIBS) -o  $@ $<

# client: simpleclient.c
# 	gcc -W -Wall -o $@ $<
# clean:
# 	rm httpd
all: httpd  
httpd: httpd.c
	gcc -g -W -Wall -pthread -o httpd httpd.c
clean:
	rm httpd