# Optimizing-LAN-routes-using-MinHeap

## Problem
During the Pandemic CoVID, the classes and labs in universities were mostly
conducted online. The load on the internet service and Local area network
(LAN) has significantly increased. It is observed in NUCES that our LAN is
not properly designed and it is not using the available resources to its fullest.
As we are familiar with the fact that the NUCES Lahore campus
consists of various buildings so the LAN needs to connect the classrooms,
labs, faculty offices in these buildings efficiently.



## Solution
### Minimum spanning tree
We have modeled this problem to a graph, where computers in classrooms,
labs and offices are represented by nodes and the networking wires that
connect them are represented by edges. The edges have weight that indicates
the length of the wire needed to connect two nodes. Your task is to take this
graph as input and design a LAN network, FLAN that covers all the nodes
with minimum wire length and do so efficiently.
