# TCP_Webserver
Bare Socket TCP Multithreaded Web server

# Java Implementation

The project has all the eclipse files attached to it.
This program upon opening the server sockets, creates a new thread of HttpRequest class upon a incoming connection.
This thread then calles the processRequest function which 
1) Buffers the data and convert into to string
2) Checks for valid type and availablity of file
3) Upon which it decides wheather to send a 404 or write bytes to socket to send.


