# Johnson's 2 Machine Algorithm

Johnson's scheduling algorithm is a method used for scheduling tasks or jobs on two machines to minimize the total completion time

-Input: Given a set of n jobs, each job j has two processing times: p1(j) for Machine 1 and p2(j) for Machine 2.

1.) Sort the jobs: Sort the jobs in increasing order of the smaller of their two processing times, i.e., p1(j) for each job j.

2.) Initialize schedules: Initialize two schedules, one for each machine, as empty schedules.

3.) Schedule the jobs: Starting from the sorted list of jobs, assign jobs to the machines one by one in the following manner:
If the job j has p1(j) ≤ p2(j), assign it to Machine 1 and add it to the Machine 1 schedule.
Otherwise, assign it to Machine 2 and add it to the Machine 2 schedule.

4.) Output: The final schedule consists of the order in which the jobs were assigned to the machines.
