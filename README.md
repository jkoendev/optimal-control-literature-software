# Literature and list of software packages for optimal control 

The list includes resources to the following topics: Automatic/algorithmic differentiation, optimal control, model-predictive control (MPC), numerical optimization, modeling for control.  The list will be updated regularly, create a pull request if you'd like to contribute.

## Literature

### Lectures

* Lecture notes: Numerical Optimal Control by Prof. Moritz Diehl [[course](https://www.syscop.de/teaching/ss2017/numerical-optimal-control)] [[pdf](https://www.syscop.de/files/2017ss/NOC/script/book-NOCSE.pdf)]
* Tutorial series by Metthew Kelly, [[web](http://www.matthewpeterkelly.com/tutorials/index.html)]
* Liberzon, Daniel. Calculus of variations and optimal control theory: a concise introduction. Princeton University Press, 2011. [[pre-print](http://liberzon.csl.illinois.edu/teaching/cvoc.pdf)]
* Videos of lectures at the University of Florida from the Spring of 2012. Dr. Anil V. Rao. [[web](http://www.anilvrao.com/Optimal-Control-Videos.html)]

### Books

* Bertsekas, Dimitri P., et al. Dynamic programming and optimal control. Vol. 1. No. 2. Belmont, MA: Athena scientific, 1995.
* Betts, J., Practical Methods for Optimal Control and Estimation Using Nonlinear Programming, SIAM, 2010
* Biegler, L. T., Nonlinear Programming, SIAM, 2010
* Model Predictive Control: Theory, Computation, and Design, 2nd Edition by Rawlings, Mayne, Diehl [[web](https://sites.engineering.ucsb.edu/~jbraw/mpc/)] [[pdf](https://sites.engineering.ucsb.edu/~jbraw/mpc/MPC-book-2nd-edition-2nd-printing.pdf)]

### Survey papers

* F. Topputo and C. Zhang, “Survey of Direct Transcription for Low-Thrust Space Trajectory Optimization with Applications,” Abstract and Applied Analysis, vol. 2014, Article ID 851720, 15 pages, 2014. [[edited](https://www.hindawi.com/journals/aaa/2014/851720/)


## Software 

### High level optimal control modeling languages and optimal control software

- Acado [[github](https://github.com/acado/acado)] [[web](http://acado.github.io/)]
- acados [[github](https://github.com/acados/acados)] [[web](http://acados.org/)]
- BOCOP [[web](https://www.bocop.org/)]
- Control toolbox, domain specific for robotics [[bitbucket](https://bitbucket.org/adrlab/ct/wiki/Home)]
- Dymos: Open-source Optimal Control for Multidisciplinary Systems [[github](https://github.com/OpenMDAO/dymos)]
- ICLOCS2 [[github](https://github.com/ImperialCollegeLondon/ICLOCS/)] [[web](http://www.ee.ic.ac.uk/ICLOCS/)] 
- Modelica with JModelica [[web](https://jmodelica.org/)] 
- OpenOCL [[github](https://github.com/OpenOCL/OpenOCL)] [[web](https://openocl.org/)] 
- PSOPT [[github](https://github.com/PSOPT/psopt)] [[web](http://www.psopt.org/)]
- Pyomo with .DAE extension [[github](https://github.com/Pyomo/pyomo)] [[web](http://www.pyomo.org/)] 
- towr, domain specific for legged robots [[github](https://github.com/ethz-adrl/towr)]
- AMPL with TACO extension (commercial)
- DIDO (commercial)
- Forces (commercial)
- GPOPS2 (commercial)
- gPROMS (commercial)
- Mujoco, domain specific for robotics/contact, simulator (commercial)
- Optimica, Dymola (commercial)
- PROPT (commercial)

### High level numerical optimization modeling languages

- CasADi [[github](https://github.com/casadi/casadi)] [[web](https://web.casadi.org/)]
- CVX, convex [[web](http://cvxr.com/cvx/)]
- Pyomo [[github](https://github.com/Pyomo/pyomo)] [[web](http://www.pyomo.org/)] 
- Yalmip [[github](https://github.com/yalmip/YALMIP)] [[web](https://yalmip.github.io/)] 

### Numerical optimization solver 

#### Non-linear programming

- Ipopt [[github](https://github.com/coin-or/Ipopt)]
- CONOPT (commercial)
- Forces (commercial)
- KNITRO (commercial)
- Matlab fmincon (commercial)
- Snopt (commercial)
- WORHP (commercial)


#### Linear, quadratic, convex programming

- ECOS [[github](https://github.com/embotech/ecos)]
- hpipm [[github](https://github.com/giaf/hpipm)]
- Sedumi [[github](https://github.com/sqlp/sedumi)]
- qpDUNES [[github](https://github.com/jfrasch/qpDUNES)]
- qpOASES [[coin-or](https://projects.coin-or.org/qpOASES)]
- SDPT3 [[web](http://www.math.nus.edu.sg/~mattohkc/sdpt3.html)]
- CPLEX (commercial)
- Gruobi (commercial)
- MINOS (commercial)
- Mosek (commercial)

#### Integer, mixed-integer programming

- Bonmin

## Automatic differentiation

- CasADi [[github](https://github.com/casadi/casadi)] [[web](https://web.casadi.org/)]
- CppAD [[github](https://github.com/coin-or/CppAD)]
- CppADCodeGen [[github](https://github.com/joaoleal/CppADCodeGen)]
- JuliaDiff [[github](https://github.com/JuliaDiff/)] [[web](http://www.juliadiff.org/)]

## Other material

- Summer School on Numerical Optimization Software (includes a long list of solvers in the slides, see repository), Hans D. Mittelmann, Moritz Diehl [[web](https://www.syscop.de/teaching/2016/summer-school-on-numerical-optimization-software)] [[repository](https://gitlab.syscop.de/teaching/NOS_public)]
- Decision tree, benchmarks for optimization software, Hans D. Mittelmann [[web](http://plato.asu.edu/)]
