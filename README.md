# QSeek
## QSeek is a local search solver designed for general mixed-integer quadratic programming (MIQP) problems, handling cases where quadratic terms may appear in the objective function, constraints, or both
## QSeek is the updated version of LS-IQCQP. Unlike its predecessor, LS-IQCQP, which primarily solves integer quadratic constrained quadratic programming (IQCQP) problems, QSeek extends its capabilities to not only solve integer problems but also mixed-integer problems.
## Author: XiangHe and Shaowei Cai
#### Local Search is an incomplete algorithm that continuously improves the quality of solutions through a finite number of iterations within a cutoff time. After the cutoff period, it outputs the found optimal objective function value and solution set.





- To use the solver,  **run ./qpsolver cutoff_time(second) filename.lp**. 





- "run.sh" is a simple example of using the solver.

  

