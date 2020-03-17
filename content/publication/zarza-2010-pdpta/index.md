---
title: "Fault-tolerant Routing for Multiple Permanent and Non-permanent Faults in HPC Systems"
date: 2010-07-01
publishDate: 2020-03-16T22:15:57.160814Z
authors: ["G. Zarza", "D. Lugones", "D. Franco", "E. Luque"]
publication_types: ["1"]
abstract: "The interconnection network communicates and links together the processing units of modern high- performance computing systems. In this context, network faults have an extremely high impact since most routing algorithms were not designed to tolerate faults. Because of this, just a single fault may stall messages in the network, preventing the finalization of applications, or may lead to deadlocked configurations. In this paper we introduce a fault-tolerant routing method designed to solve a large number of dynamic per- manent and non-permanent link faults. As failures appear randomly during system operation, our method provides escape paths for the stalled messages and, at the same time, avoids deadlock occurrences. Our proposal avoids faulty areas by means of multipath routing approaches, taking advantage of the communication path redundancy, as long as alternative paths are available. Performance evaluation consists of synthetic test scenar- ios for proving correctness, and test scenarios based on the availability traces of real high-performance systems. Experiments show that our method allows applications to successfully complete their executions even in the presence of a large number of faults, given performance degrada- tions below 3% for a 1024-node system with up to 200 simultaneous link failures."
featured: false
publication: "*Proceedings of the International Conference on Parallel and Distributed Processing Techniques and Applications (PDPTA)*"
tags: ["Interconnection Networks", "Fault Tolerance", "Adaptive Routing"]
---

