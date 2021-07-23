# Traveling-Salesman
The project uses the method of Simulated Annealing (SA) to solve the infamous Traveling Salesman Problem. The problem description itself is given at the beginning of the notebook.
Read further to know how SA works. 

The method of Simulated Annealing is an optimization algorithm which has as its aim the determination of a global optimum. 
Finding a global optimum of a highly non-linear non-convex function, say f(x), is a rather diffcult task when the solution space is huge. "Greedy" methods such as Gradient Descent face the problem of getting stuck in the local optima and are therefore not suitable for such senarios. Simulated Annealing introduces stochasticity to the optimization process by drawing an analogy from the metallurgical process of annealing. 

The system starts at a high "Temperature" and accepts the new solutions based on the Boltzmann Probability distribution, P= exp(-dE/T), where dE is the change
in energy or in this case in the value of f(x). In the beginning, the bad solutions are also accepted with a high probability allowing a broader search of the 
solution space and also enabling the algorithm to escape local optima. The temperature is then slowly decreased and the algorithm tends to a greedy approarch 
where a good solution is accepted with a higher probability. This approach, called the Metropolis Algorithm, brings us extremely close to the global optima with a lot less computational expense.
  

# Required libraries
This project uses a rather simple framework to achieve the goal. The libraries required are numpy, matplotlib and IPython. They can be downloaded using either
the pip or Conda installer. 
