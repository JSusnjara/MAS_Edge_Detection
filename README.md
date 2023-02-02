# MAS_Edge_Detection
A project from Multi-Agent Systems course - Edge Detection implementation.

It uses 3 types of agents:
- Scout - responsible for finding edges using Sobel filter
- EdgeFollower - responsible for following found edge using gradient contrast and standard deviation
- Manager - responsible for initialization and communication (assignment of responsibilities) between all the agents
