# Traveling-Salesman
The project uses the method of Simulated Annealing (SA) to solve the infamous Traveling Salesman Problem. The problem description itself is given at the beginning of the notebook.
Read further to know how SA works. 

The method of Simulated Annealing is an optimization algorithm which has as its aim the determination of a global optimum. 
Finding a global optimum of a highly non-linear non-convex function is a rather diffcult task when the solution space is huge. "Greedy" methods such as Gradient
Descent face the problem of getting stuck in the local optimum and are therefore not suitable for such senarios. Simulated Annealing introduces stochasticity to
the optimization process by drawing an analogy from the metallurgical process of annealing. 

The system starts at a high "Temperature" and selects the new solutions based on the Boltzmann Probability distribution.



# Required libraries
This project uses a rather simple framework to achieve the goal. The libraries required are numpy, matplotlib and IPython. They can be downloaded using either
the pip or Conda installer. 
