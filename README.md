# bankers-algorithm-simulator

Developed a web simulator which takes No. of Resources Types and No. of Processes and provides the result whether the process can be completed by avoiding deadlock using Banker's Safety Algorithm by using HTML, CSS, Javascript, Bootstrap, and JQuery.

The Banker algorithm, sometimes referred to as the detection algorithm, is a resource allocation and deadlock avoidance algorithm developed by Edsger Dijkstra that tests for safety by simulating the allocation of predetermined maximum possible amounts of all resources, and then makes an "s-state" check to test for possible deadlock conditions for all other pending activities, before deciding whether allocation should be allowed to continue.


For the Banker's algorithm to work, it needs to know three things:

How much of each resource each process could possibly request[MAX] 
How much of each resource each process is currently holding[ALLOCATED] 
How much of each resource the system currently has available[AVAILABLE]

