# iPerfer
The Assignment of CS640 Spring 2015

Assignment 1: Sockets, Mininet, & Performance

Part 1: Write Iperfer

Client Mode

  Iperfer -c -h <server hostname> -p <server port> -t <time>
 
  Error: missing or additional arguments
  
  If the server port argument is less than 1024 or greater than 65535, you should print the following
  and exit:
  range 1024 ≤ server port ≤ 6553
 
  For example:
  sent=6543 KB rate=5.234 Mbps

Server Mode:
  
  Iperfer -s -p <listen port>
  
  Error: missing or additional arguments
  
  If the listen port argument is less than 1024 or greater than 65535, you should print the following
  and exit:
  Error: port number must be in the range 1024 to 65535

http://pages.cs.wisc.edu/~agember/cs640/s15/assign1/
