---
title: "FT-DRB: A Method for Tolerating Dynamic Faults in High-Speed Interconnection Networks"
date: 2010-02-01
publishDate: 2020-03-16T22:15:57.159714Z
authors: ["Gonzalo Zarza", "Diego Lugones", "Daniel Franco", "Emilio Luque"]
publication_types: ["1"]
abstract: "The intensive and continuous use of high-performance computing systems for executing computationally intensive applications, coupled with the large number of elements that make them up, dramatically increase the likelihood of failures during their operation. The interconnection network is a critical part of such systems, therefore, network faults have an extremely high impact because most routing algorithms are not designed to tolerate faults. In such algorithms, just a single fault may stall messages in the network, preventing the finalization of applications, or may lead to deadlocked configurations. This paper introduces a novel fault-tolerant routing method provided with a new deadlock avoidance technique designed to solve an unbounded number of faults appearing at random during system operation. Our method provides escape paths for the stalled messages. In addition, the routing algorithm configures alternative paths to avoid the faulty areas taking advantage of communication path redundancy by means of multipath routing approaches. Deadlock avoidance is achieved by adding a small-sized queue and applying a simple set of actions when accessing output buffers with limited free space. Experiments show that our method allows applications to successfully finalize their execution in the presence of several number of faults, with an average performance value of 96% compared to the fault-free scenarios."
featured: false
publication: "*18th Euromicro International Conference on Parallel, Distributed and Network-Based Computing (PDP)*"
tags: ["fault tolerance", "interconnection networks", "multipath routing"]
doi: "10.1109/PDP.2010.65"
---

