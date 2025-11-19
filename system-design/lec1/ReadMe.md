# Distributed Systems (MIT Couse)

Follow the video lecture seers [here](https://www.youtube.com/playlist?list=PLrw6a1wE39_tb2fErI4-WkMbsvGQk9_UB).

## Lecture 1: Introduction
Video: [Lecture 1: Introduction](https://youtu.be/cQP8WApzIQQ?si=Q8PZxjqJGhzs4OO3)
Paper: [MapReduce](/mapreduce-paper.pdf)


**Note:** If you can solve a problem without the need of more than one computer, that is *probably* the better solution.



 **Motivations:** 
 * Critical infrastructure is built out of distributed systems
 * *parellism* - multiple tasks at the same time
 * *fault tolerance* - if one computer fails there is redundency
 * *physical constraints* - geographic constrinats
 * *security/isolation* - only want to interact with other computers when necessary


**Challenges:**
* *concurrency* - how do you "share" resources...
* *partial failure* - if one computer fails the whole system may not fail
* *performance* - may be difficult to get the performance 

**Infrastructure**
* *Storage* - 
* *Communication* - Tool to build distributed systems
* *Computation* - 

**Goal:** Build **abstraction** that hides the distrubited nature of the systems

**Implementation:**
* remoce procedure call (RPC) - Mask the fact that you are communicating over network
* threads - a way of structuring concurrent operations
* concurrency control (e.g., locks)

**Performance:**
* *Scalability* - Ratio *computers:throughput*


**Fault Tolerance:**
* 















