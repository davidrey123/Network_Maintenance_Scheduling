# Network_Maintenance_Scheduling
Instances for the bilevel network maintenance scheduling problem

This repository contains baseline scenarios for the bilevel network maintenance scheduling problem. The bilevel maintenance scheduling problem aims to find the optimal coordination of maintenance projects in a transport network under a user-equilibrium traffic assignment. Each maintenance project consists of a list of network links, a link capacity reduction factor and a project duration. If a maintenance project is active, the capacity of all links affected by this project is reduced accordingly for the duration of the project.

Instances are named as follows: **Network_P.txt** where **Network** is the name of the transport network and **P** is the number of maintenance projects.

Each file refers to a transport network publicly available at https://github.com/bstabler/TransportationNetworks. Each file contains the list of links affected for each project. The link capacity reduction factor and the duration of projects is not provided. 

These instances have been used in Rey et al. (2019).

Rey, D., Bar-Gera, H., Dixit, V.V. and Waller, S.T., 2019. A branch-and-price algorithm for the bilevel network maintenance scheduling problem. Transportation Science, 53(5), pp.1455-1478.
