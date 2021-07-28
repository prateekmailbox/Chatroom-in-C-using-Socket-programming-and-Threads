# Chatroom-in-C

A simple Chatroom built in C programming language. The program has two files - <b>server.c</b> and <b>client.c</b>. The program is built uses multithreading for handling multiple clients.

# Run the program
Just simply run the Makefile using this command. <br/>

For compiling client and server C files , write the code given in Makefile on the Terminal. <br/>

gcc -Wall -g3 -fsanitize=address -pthread server.c -o server
gcc -Wall -g3 -fsanitize=address -pthread client.c -o client


