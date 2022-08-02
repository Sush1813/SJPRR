# SJPRR
Shortest Job Prioritized Round Robin Algorithm
Round Robin algorithm (RR) is the widely used scheduling algorithm in multitasking and real time environment and cloud environments.In RR, much time is lost in the form
of switching time and hence an algorithm is proposed where a dynamic and optimal time quantum is allocated for each process in the ready queue based on its requirement. This paper describes 
about the proposed algorithm,Shortest Job Prioritised Round Robin Algorithm(SJPRR) which is written using base idea of three CPU Scheduling Algorithms and is expected to result in
lesser average TAT and average WT.

PROBLEM STATEMENT
The algorithm devised intends to allocate dynamic and
optimal time quantum for each process in the ready queue
based on its requirement to save excess time lost as switching
time
A. Dynamic quantum allocation
Performance of Round-Robin algorithm highly depends on a
Time Quantum, which is a predefined amount of time assigned
by system to every task to be executed.If a small time quantum
is chosen then context switch is high and a larger time quantum
leads to First come first serve algorithm.So, the performance
of the system totally depends upon the choice of optimal time
quantum. The new approach of RR scheduling algorithm is
based on using dynamic time quantum, which will reduce
waiting time and the number of context switches in order to
improve the system overall performance.
B. Proposed improvement in RR algorithm
To overcome the previously mentioned disadvantages of
RR algorithm, the following additional improvements are
proposed.
• To find the run time/burst time of each process in the
ready state queue.
• Find an optimal time quantum that is not so small for
the longest process as well as not too long for smallest
process
• Assign the dynamically optimal time quantum and run
the processes.
