# Network_Maintenance_Scheduling
Instances for the bilevel network maintenance scheduling problem

This repository contains instances for benchmarking algorithms for the bilevel network maintenance scheduling problem. 
The bilevel maintenance scheduling problem aims to find the optimal coordination of maintenance projects in a transport network under a user-equilibrium traffic assignment. 
Each maintenance project consists of a list of network links and a link capacity reduction factor. 
If a maintenance project is active, the capacity of all links affected by this project is reduced accordingly.

Each file refers to a transport network publicly available at https://github.com/bstabler/TransportationNetworks. 
Instances are named as follows: "Network_P.txt" where Network is the name of the transport network and P is the number of maintenance projects.

Each file contains the list of links affected for each project

These instances were used in the publication Najmi, Ali, David Rey, and Taha H. Rashidi. "Novel dynamic formulations for real-time ride-sharing systems." Transportation Research Part E: Logistics and Transportation Review 108 (2017): 122-140. https://doi.org/10.1016/j.tre.2017.10.009. In this paper, trip requests with an ID less than 100,000 are used as drivers' announcements whereas remaining trip requests are used as riders' announcements.
