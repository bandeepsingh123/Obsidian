Date : 2025-06-30  Time : 09:19

Status : #inProgress  

## Socket Programming Research
 What is a socket?
 - programs use sockets to communicate(send and receive data) using standard Unix file descriptors

Types of sockets()?
-DARPA Internet addresses (Internet Sockets)
-path names on a local node (Unix Sockets),
-CCITT X.25 addresses (X.25 Sockets that you can safely ignore)

Types of Internet Sockets:
- Stream Sockets : "SOCK_STREAM" 
- DataGram Sockets : "SOCK_DGRAM" ,  also called connection-less sockets

Stream Sockets are reliable two- way connected communication streams. i.e. output 1 2 from one socket will be received as 1 2 by receiver socket



## Reference