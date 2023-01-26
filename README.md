# Disk-Scheduling-Algorithm-Analysis
The present piece of investigation documents the comparative analysis of six different disk scheduling algorithms viz. First Come First Serve (FCFS), Shortest Seek Time First (SSTF), Scan, C-Scan, Look and C-look disk scheduling by comparing their head movement in different runs.
<br>
<br>
OSSP Project (Operating Systems and System Programming)

---

### :woman_technologist: Introduction

The file system can be viewed logically in three different divisions i.e. user, programmer interface to the file system and secondary storage structure. The lowest level of the file system is secondary storage structure and disk is the main secondary storage device that is generally divided into tracks, cylinders and sectors and stores the data permanently. The I/O operation depends on the computer system, the operating system, and the nature of the I/O channel and disk controller hardware. 
The user programs make use of the data on the disk by means of I/O requests. Data is stored on both surfaces of a series of magnetic disks called platters that are connected by a single spindle. The surface of a platter is logically divided into tracks that are further subdivided into sectors and the set of tracks that are at one arm position form a cylinder. 
One read-write head per disk surface is used to access the data and all read-write heads are attached to a single moving arm. The segment of the disk surface where the data is read or written must revolve under the read-write head for accessing the data. The key responsibility of the operating system is to efficiently use the hardware of the computer system. For most disks, the seek time leads to latency time and transfer time, so reducing the mean seek time can improve system performance to a large extent. 
 


---
### :hammer_and_wrench: Problem Statement

A process needs two types of time, CPU time and I/O time. For I/O, it requests the Operating system to access the disk. However, the operating system must be fair enough to satisfy each request and at the same time, the operating system must maintain the efficiency and speed of process execution. So, it must determine which request should be satisfied next. 
Disk scheduling is important because: 
•	Multiple I/O requests may arrive by different processes and only one I/O request can be served at a time by the disk controller. Thus other I/O requests need to wait in the waiting queue and need to be scheduled. 
•	Two or more request may be far from each other so can result in greater disk arm movement. 
•	Hard drives are one of the slowest parts of the computer system and thus need to be accessed in an efficient manner. 


---
### :telescope: Objective

In multiprogramming systems, processes running concurrently may generate requests for reading and writing disk records. The operating system handles these I/O requests from the queue and processes them one by one. The algorithm used to choose which I/O request is going to be fulfilled earliest is called disk scheduling algorithm. The different disk scheduling algorithms are First Come First Serve, Shortest Seek Time First, Scan, Look, Circular Scan and Circular Look. The main objectives for any disk scheduling algorithm are minimizing the response time and maximizing the throughput.  
### :zap: Conclusion

We have calculated the average total head movement after entering the various runs for the requests of different algorithms because total head movement is the criteria for analyzing the disk scheduling algorithms. After comparing the total head movement of various algorithms, we have found that the Shortest Seek Time First disk scheduling algorithm has the least average head movement than the others discussed above in context to total head movement. 

---

<div id="header" align="center">
  
  <img src="https://komarev.com/ghpvc/?username=vaishaliranjan&style=flat-square&color=blue" alt=""/>
  
<div>




