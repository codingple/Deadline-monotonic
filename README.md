# Deadline-monotonic
#### An implementation of Deadline-monotonic scheduling in C

### Description  
This program calcuates response time and schedulability of periodic tasks using Deadlin-monotonic scheduling. 
Assuming all tasks arrive at the same time, they are processed in the shortest deadline order.
With the given information of tasks, '_I_' is caculated to find out if the task is schedulable.
The response time is setted to -1 when the '_t_' converges to infinity.  
> Note that the _I_ denotes _interference time_ of _**Definition 1**_ and _t_ is described in _**Definition 2**_ :  
> [Deadline Monotonic Scheduling](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.53.8928&rep=rep1&type=pdf)  
