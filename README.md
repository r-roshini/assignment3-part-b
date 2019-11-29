# assignment3-part-b
The most fundamental responsiblity of UDP is to extend IP's delivery service between two end systems to a delivery service between two 
process running on end systems.Extending host-to-host delivery to process-to-process delivery is called transport-layer multiplexing and
demultiplexing.It also provides integrity checking by including error-detection fields in their segments headers.
UDP is an unreliable service-it does not guarantee that data sent by one process will arrive intact to the destination process

challenges:
have few knowledge about udp programming
found difficult to implement in c# language
so we reffered microsoft.docs for udp connection in c# and implemented this in the previous program(Leaky bucket-part A)
again unable to implement the ping request

reference:
https://docs.microsoft.com>dotnet
     for udp connections in java
lab manual for leaky bucket
