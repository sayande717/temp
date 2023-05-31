# temp
Repository for storing temporary code.

Syntax:
[[START: #N]]
text
[[END: #N]]
----------

[[START: #1]]

[NULL] - 
53.txt - Message queue creation
53.1.c - Create a message queue with message get (msgget()) function & IPC_CREAT. Also show the perror function that generates an error when the message queue creation fails.
53.2.c - IPC queue creation with file permissions.
53.3.c - IPC message queue creation with flag IPC_CREAT and IPC_EXCEL.

[NULL] - 
54.txt - Sending & Receiving messages.
54.1-2.c - Write a program to send a text message from a terminal to another terminal via IPC message queue. Hint: Create a message queue using msgget() function, send & receive using msgsnd(), msgrcv().
54.1.c - Receive message
54.2.c - Send message

[NULL] - 
55.1-2.c - Write a program to send foud successive messages from the sender. The reciver will accept those messages and print them after another as an output string. Receiver will not reply for those messages.
55.1.c - Sender
55.2.c - Receiver

[NULL] - 
56.1.c - Creation of a one-way pipe in a single process.
56.2.c - Creation of a one-way pipe in two processes.
56.3.c - Creation of a two way pipe between two processes.
56.4.c - Write a program to create a 2 way pipe between 2 processes, and check if it is an armstrong number or not.

[NULL] - 
57.1-2.c - Write a program for IPC through FIFO between client and server and find the vowels and consonants from an input sentence and display total number of vowels and consonants in the sentence.
57.1.c - Client
57.2.c - Server

[NULL] - 
58.1-2.c - Write a program to design Berkeley sockets for interprocess communication between client and server across the network.
58.1.c - Client
58.2.c - Server

[NULL] -
59.1-2.c - Design a TCP iterative client and server application to reverse the given input sentence.
59.1.c - Client
59.2.c - Server

[NULL] - 
60.1-2.c - Write a program to implement stop and wait protocol in data link layer.
60.1.c - Stop Wait Receiver
60.2.c - Stop Wait Sender

[NULL] - 
61.1-2.c - Write a program to implement Go Back N Protocol in the data link layer.
61.1.c - Go Back N Receiver
61.2.c - Go Back N Sender
[[END: #1]]
