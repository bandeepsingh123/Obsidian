Date : 2025-07-03  Time : 15:47

Source : beej's guide to network programming

Status : #inProgress   
## Information

what are sockets?
a way/method used by programs to communicate( send and receive data )

Everything in unix is a file

file descriptor -  an integer associated with an open file 

everything on UNIX is a file 

types of sockets - DARPA internet sockets , CCITT X.25 addresses

types of internet sockets :
- stream sockets referred to as SOCK_STREAM
- datagram sockets referred to as SOCK_DGRAM aslo called  connectionless socket

stream sockets are reliable and two way connected communication stream

output two items into the stream socket in order 1 2 they will arrive in the order 1 2  at the opposite end

stream socket are also error free

uses of stream socket ?
use in telent and ssh applications and web browsers use HyperText Transfer Protocol( HTTP ) uses stream sockets to get pages

stream sockets achieve this with the help of "The Transmission Control Protocol"