# CoEdge
The main source code of the paper "CoEdge: A Collaborative Architecture for Efficient Task Offloading among Multiple Edge Service Providers". Warmly invite scholars to share valuable feedback and suggestions. 

Considering the practical aspects of task offloading in edge network, the key challenges in task offloading involve determining whether tasks require scheduling and identifying the appropriate computing node for processing. Following task scheduling, the computing node provides pricing based on the scheduling decision.

This can be broken down into two interrelated sub-problems: (1) task scheduling problem : under the collaborative architecture, how to efficiently assign ESPs for computing tasks to expedite service response? (2) service pricing problem: how to establish an optimal service pricing strategy for ESPs to maximize their profits? 

These sub-problems are inherently interconnected through the matching relationship between tasks and ESPs.

We regard the task scheduling problem as Delay-aware Scheduling Optimization (DSO), and through rigorous mathematical proof, we establish it as NP-hard, thereby designing an approximate algorithm SATS for its solution.

We consider the service pricing problem as Service-aware Pricing Optimization (SPO), and through rigorous mathematical proof, we establish it as NP-hard, thereby designing an approximate algorithm PASP for its solution. 

The output of SATS, specifically the task-ESP matching results, serves as the input for PASP, thereby aligning with the intrinsic correlation between the two sub-problems.
