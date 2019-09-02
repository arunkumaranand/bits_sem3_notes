# DISTRIBUTED COMPUTING
Course No: SS ZG526
Instructor: Chitranjan Hota

## Course Objective

1. various h/w architecture for building distributed systems and their communication models
2. Understand the design aspect of various s/w application that can deployed on various distributed system
3. Undestand the complexities and resource management issues that are critical in a large distributed system
4. Algorithm aspect of building/designing distributed systems in domians like IoT, P2P, Cluster, Grid computing etc..

## Text Books

1. TextBook 1: [Distributed Computing: Principles, Algorithms, and Systems, Ajay D](https://www.amazon.in/Distributed-Computing-Principles-Algorithms-Systems/dp/0521189845)
2. Reference 1: [P2P Networking and Applications](https://www.amazon.in/Networking-Applications-Morgan-Kaufmann-Hardcover/dp/0123742145)
3. Reference 3: [Distributed and Cloud Computing: From Parallel processing to the Internet of Things](https://www.amazon.in/Distributed-Cloud-Computing-Parallel-Processing/dp/9381269238/ref=sr_1_1?keywords=Distributed+and+Cloud+Computing%3A+From+Parallel+processing+to+the+Internet+of+Things&qid=1567394977&s=books&sr=1-1)

## Course Content

### M1: Introduction to Distributed Computing 

1. Introduction to Distributed computing
2. Motivation, Multiprocessor Vs Multicomputer Systems
3. Distributed Communication Model; RPC
4. Design issues and challenge

### M2: Logical Clocks & Vector clocks

1. A framework for a system of logical clock
2. Scalar time, Vector time.
3. Implementation of Logical and Vector clocks, Efficient implementation of Vector clocks.
4. Physical Clock synchronization: NTP

### M3: Global state and snapshot recording algorithms

1. System model and definitions
2. Snapshot recording algorithms for FIFO channels
3. Snapshot recording algorithms for non-FIFO channels
4. Necessary and sufficient conditions for consistent global snapshots
5. Classifications and basic concepts
6. Elementary graph algorithms, Synchronizers
7. Maximal Independent set, and Connected dominating set

### M4: Message ordering and Termination detection

1. Message ordering paradigms
2. Group Communication
3. Protocols for ensuring Causal order of messages
4. Total order
5. Application level multicast
6. Termination detection using distributed snapshots
7. Termination detection using weight throwing
8. A spanning-tree based termination detection algorithm

### M5: Distributed Mutual Exclusion

1. Introduction and Preliminaries
2. Assertion based: Lamport’s algorithm, and Ricart-Agrawala’s algorithm
3. Assertion based: Maekawa’s algorithm
4. Token based: Suzuki-Kasami’s broadcast based algorithm
5. Token based: Raymond’s tree based algorithm

### M6: Deadlock detection

1. Models of distributed deadlock
2. Chandy-Misra-Haas deadlock detection for AND model
3. Chandy-Misra-Haas deadlock detection for OR model
4. Deadlock resolution

### M7: Consensus and Agreement Algorithms

1. Problem definition
2. The Byzantine agreement and other consensus problems
3. Overview of Results
4. Agreement in failure-free system (synchronous or asynchronous)
5. Agreement in (message-passing) synchronous systems with failures

### M8: Peer-to-Peer computing and Overlay graphs

1. Introduction
2. Data indexing and Overlays
3. Unstructured Overlays
4. Structured Overlays: CHORD DHT
5. Design issues of P2P overlays
6. Security concerns from P2P networks
7. Mitigating security risks in P2P networks

### M9: Cluster Computing & Grid Computing

1. Cluster development trends
2. Design objectives of Computer clusters
3. Cluster organization and resource sharing
4. Node architecture and MPP packaging
5. Cluster system interconnects
6. Hardware, software and Middle ware support
7. GPU Clusters for massive parallelism
8. Cluster job and resource management
9. Grid architecture and service modeling
10. Grid resource management and brokering

### M10: Internet of Things

1. IoT for Ubiquitous computing, RFID, Sensors and ZigBee technologies,
2. Applications of IoT (smart buildings, cyber-physical systems)
3. Graph theoretic analysis of social networks; Facebook, and Twitter case studies

## Leraning Outcome

1. Understanding of middleware platforms like RPC(Sun RPC, Java RMI, etc) for implementing communication models over distributed systems. 
2. Understanding the need of Logical clocks and their usages in building distributed systems and its’ components.
3. Understanding of Mutual exclusion primitives, Agreement protocols, and deadlock handling scenarios in distributed systems.  
4. Understanding of search, storage, communication, efficiency and other related issues in paradigms like P2P, Cluster, Grid, and IoT.

## Contact Session Plan

## Lab Details
1. Mod 1
    To understand Remote procedure call in client server environment.
2. Mod 2 
    To understand Lamport clock to determine order of events in distributed system
3. Mod 6
    To understand Lamport’s  distributed mutual exclusion algorithm
4. Mod 7
    To understand Byzantine agreement algorithm to determine tolerance of systems to faulty nodes
5. Mod 8
    To understand Peer2Peer distributed applications
6. Mod 9
    To understand the concept of clustered network can be implemented over HTTP/HTTPS protocol
7. Mod 10
    A security system that sends an email once an intrusion is detected