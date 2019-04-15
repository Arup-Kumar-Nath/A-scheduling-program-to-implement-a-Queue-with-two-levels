# A-scheduling-program-to-implement-a-Queue-with-two-levels
It is a scheduling program to implement a Queue with two levels:  
Level 1: Fixed priority pre-emptive Scheduling ; 
Level 2: Round Robin Scheduling 
For a Fixed priority preemptive Scheduling, the Priority 0 is highest priority. If one process P1 is scheduled and running, another 
process P2 with higher priority comes, the New process (high priority) process P2 preempts currently running process P1 and process 
P1will go to second level queue. Time for which process will strictly execute must be considered in the multiples of 2.
All the processes in second level queue will complete their execution according to round robin scheduling. 
Constraints : 
1. Queue 2 will be processed after Queue 1 becomes empty.
2. Priority of Queue 2 has lower priority than in Queue 1.
