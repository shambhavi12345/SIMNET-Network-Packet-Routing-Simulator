# SIMNET-Network-Packet-Routing-Simulator
The project involves the designing and simulation of a network packet routing system illustrated using a Tkinter GUI. 


The project involves the designing and simulation of a network packet routing system illustrated using a Tkinter GUI.
The router is parameterized to accept 'A' packet routing connections at any time.The packets take 'B' time to be routed through the router.Each device connected to the router will wait up to 'C' time for the packet to be routed to its destination.


                IMPLEMENTATION OF THE PROJECT
The router is parameterized to accept 'A' packet routing connections at any time. The packets take 'B' time to be routed through the router. Each device connected to the router will wait up to 'C' time for the packet to be routed to its destination.

PRIORITY LEVELS: The define three levels of prioritization, so that high-priority packets like those for voice and video calls can route through before lower-priority packets like standard file downloads. Number of devices on the network = n


TYPES OF PACKETS: Each device generates the following types of packets:
Xv video calling packets,
Xs standard priority packets, Xl low priority packets at an Xi interval.
Higher priority packets will be able to jump the queue without pre-empting the low priority packets.


VARIABLES USED: A = 6, B = exponentially-modified normal continuous random variable at location 1 and scale 1.5, C = 3 ,Xv = uniform discrete random variable between [2,10] ,Xs=uniform discrete random variable between [2,10] ,Xl = uniform discrete random variable between ,[2,10] Xi = binomial discrete random variable with n at 10 and p at 0.5

GUI: The GUI is designed using the Tkinter library and its various functions. The simulator works just like a chatbot with the user end and the server end for sending and receiving requests, respectively.



APPROACH:
Here, we will generate the packets and get the number of packets. Thereafter, we will run a simulation to find the average packets that pass through. Then, we will get the source of the packets and the time required to get through.
