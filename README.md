Floodlight SDN(Software Defined Network) open source controller.

- Floodliight by default has round-robin load balancer algorithm, I changed the load balancer algorithm to random and tested it with couple of different topologies using mininet. 
- I also implemented load balancer statistics display using HTML and CSS. This would display the source and destination Ip address and other details of the packets routed in the floodlight through loadbalancer, it also displays the path taken by the packet to each the destination.

The source code of methods and classes that are changed in the actual source code of floodlight are updated here, this project was to analyze the open source project, their modules, trace and try to implement something new in it, and I could successfully accomplish it.

