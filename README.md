# Deadline-monotonic
#### An implementation of Deadline-monotonic scheduling in C

### Description  
This program calcuates response time and schedulability of periodic tasks using Deadline-monotonic scheduling. 
Assuming all tasks arrive at the same time, they are processed in the shortest deadline order.
With the given information of tasks, '_I_' is caculated to find out if the task is schedulable.
The response time is setted to -1 when the '_t_' converges to infinity.  
> Note that the _I_ denotes _interference time_ of **Definition 1** and _t_ is described in **Definition 2** :  
> [Deadline Monotonic Scheduling](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.53.8928&rep=rep1&type=pdf)  
  
### Input  
This program loads "input.txt", which contains the number of tasks at the first line and (computation time, deadline, period) of a single task each line. In addition, the tasks are sorted by the deadline before the begining.  
  
