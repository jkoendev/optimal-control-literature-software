# Literature and list of software packages for optimal control 

The list includes resources to the following topics: Automatic/algorithmic differentiation, optimal control, model-predictive control (MPC), numerical optimization, modeling for control.  The list will be updated regularly, create a pull request if you'd like to contribute.

## Literature

* Bertsekas, Dimitri P., et al. Dynamic programming and optimal control. Vol. 1. No. 2. Belmont, MA: Athena scientific, 1995.
* Betts, J., Practical Methods for Optimal Control and Estimation Using Nonlinear Programming, SIAM, 2010
* Biegler, L. T., Nonlinear Programming, SIAM, 2010
* Lecture notes: Numerical Optimal Control by Prof. Moritz Diehl [[course](https://www.syscop.de/teaching/ss2017/numerical-optimal-control)] [[pdf](https://www.syscop.de/files/2017ss/NOC/script/book-NOCSE.pdf)]
* Liberzon, Daniel. Calculus of variations and optimal control theory: a concise introduction. Princeton University Press, 2011. [[pre-print](http://liberzon.csl.illinois.edu/teaching/cvoc.pdf)]
* Videos of lectures at the University of Florida from the Spring of 2012. Dr. Anil V. Rao. [[web](http://www.anilvrao.com/Optimal-Control-Videos.html)]
* Book: Model Predictive Control: Theory, Computation, and Design, 2nd Edition by Rawlings, Mayne, Diehl [[web](https://sites.engineering.ucsb.edu/~jbraw/mpc/)] [[pdf](https://sites.engineering.ucsb.edu/~jbraw/mpc/MPC-book-2nd-edition-2nd-printing.pdf)]

## Software 

### High level optimal control modeling languages

- Pyomo with .DAE extension [[github](https://github.com/Pyomo/pyomo)] [[web](http://www.pyomo.org/)] 
- OpenOCL [[github](https://github.com/OpenOCL/OpenOCL)] [[web](https://openocl.org/)] 
- ICLOCS2 [[github](https://github.com/ImperialCollegeLondon/ICLOCS/)] [[web](http://www.ee.ic.ac.uk/ICLOCS/)] 
- Modelica with JModelica [[web](https://jmodelica.org/)] 
- Acado [[github](https://github.com/acado/acado)] [[web](http://acado.github.io/)]
- PSOPT [[github](https://github.com/PSOPT/psopt)] [[web](http://www.psopt.org/)]
- BOCOP [[web](https://www.bocop.org/)]
- ADRL Control toolbox, domain specific for robotics [[bitbucket](https://bitbucket.org/adrlab/ct/wiki/Home)]
- ADRL towr, domain specific for legged robots [[github](https://github.com/ethz-adrl/towr)]
- PROPT (commercial)
- DIDO (commercial)
- gPROMS (commercial)
- Forces (commercial)
- AMPL with TACO extension (commercial)
- Mujoco, domain specific for robotics/contact, simulator (commercial)
- Optimica, Dymola (commercial)
- GPOPS2 (commercial)

### High level numerical optimization modeling languages

- Yalmip [[github](https://github.com/yalmip/YALMIP)] [[web](https://yalmip.github.io/)] 
- CasADi [[github](https://github.com/casadi/casadi)] [[web](https://web.casadi.org/)]
- Pyomo [[github](https://github.com/Pyomo/pyomo)] [[web](http://www.pyomo.org/)] 
- CVX, convex [[web](http://cvxr.com/cvx/)]

### Numerical optimization solver 

#### Non-linear programming

- Ipopt [[github](https://github.com/coin-or/Ipopt)]
- Snopt (commercial)
- Forces (commercial)
- Matlab fmincon (commercial)
- WORHP (commercial)
- KNITRO (commercial)
- CONOPT (commercial)


#### Linear, quadratic, convex programming

- Sedumi [[github](https://github.com/sqlp/sedumi)]
- qpOASES [[coin-or](https://projects.coin-or.org/qpOASES)]
- qpDUNES [[github](https://github.com/jfrasch/qpDUNES)]
- hpipm [[github](https://github.com/giaf/hpipm)]
- ECOS [[github](https://github.com/embotech/ecos)]
- SDPT3 [[web](http://www.math.nus.edu.sg/~mattohkc/sdpt3.html)]
- CPLEX (commercial)
- Gruobi (commercial)
- MINOS (commercial)
- Mosek (commercial)

#### Integer, mixed-integer programming

- Bonmin

## Automatic differentiation

- CasADi [[github](https://github.com/casadi/casadi)] [[web](https://web.casadi.org/)]
- JuliaDiff [[github](https://github.com/JuliaDiff/)] [[web](http://www.juliadiff.org/)]
- CppAD [[github](https://github.com/coin-or/CppAD)]
- CppADCodeGen [[github](https://github.com/joaoleal/CppADCodeGen)]


## Other material

- Summer School on Numerical Optimization Software (includes a long list of solvers in the slides, see repository), Hans D. Mittelmann, Moritz Diehl [[web](https://www.syscop.de/teaching/2016/summer-school-on-numerical-optimization-software)] [[repository](https://gitlab.syscop.de/teaching/NOS_public)]
- Decision tree, benchmarks for optimization software, Hans D. Mittelmann [[web](http://plato.asu.edu/)]
