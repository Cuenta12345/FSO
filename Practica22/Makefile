cocos3 : cocos3.c winsuport2.o winsuport2.h memoria.o memoria.h
	gcc -Wall cocos3.c winsuport2.o memoria.o -o cocos3 -lcurses -lpthread

Fantasmas3 : Fantasmas3.c winsuport2.o winsuport2.h memoria.o memoria.h
	gcc -Wall Fantasmas3.c winsuport2.o memoria.o -o Fantasmas3 -lcurses

cocos4 : cocos4.c winsuport2.o winsuport2.h memoria.o memoria.h semafor.o semafor.h
	gcc -Wall cocos4.c winsuport2.o memoria.o semafor.o -o cocos4 -lcurses -lpthread

Fantasmas4 : Fantasmas4.c winsuport2.o winsuport2.h memoria.o memoria.h semafor.o semafor.h
	gcc -Wall Fantasmas4.c winsuport2.o memoria.o semafor.o -o Fantasmas4 -lcurses

winsuport2.o : winsuport2.c winsuport2.h 
	gcc -Wall -c winsuport2.c -o winsuport2.o

memoria.o : memoria.c memoria.h
	gcc -Wall -c memoria.c -o memoria.o 

semafor.o : semafor.c semafor.h
	gcc -Wall -c semafor.c -o semafor.o

clean:
	rm -f cocos3 Fantasmas3 cocos4 Fantasmas4 winsuport2.o memoria.o semafor.o
