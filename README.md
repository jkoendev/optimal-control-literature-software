# Literature and list of software packages for optimal control 

The list includes resources to the following topics: Automatic/algorithmic differentiation, optimal control, model-predictive control (MPC), numerical optimization, modeling for control.  The list will be updated regularly.

## Literature

* Lecture notes: Numerical Optimal Control by Prof. Moritz Diehl [[course](https://www.syscop.de/teaching/ss2017/numerical-optimal-control)] [[pdf](https://www.syscop.de/files/2017ss/NOC/script/book-NOCSE.pdf)]
* Book: Model Predictive Control: Theory, Computation, and Design, 2nd Edition by Rawlings, Mayne, Diehl [[web](https://sites.engineering.ucsb.edu/~jbraw/mpc/)] [[pdf](https://sites.engineering.ucsb.edu/~jbraw/mpc/MPC-book-2nd-edition-2nd-printing.pdf)]
* Biegler, L. T., Nonlinear Programming, SIAM, 2010
* Betts, J., Practical Methods for Optimal Control and Estimation Using Nonlinear Programming, SIAM, 2010

## Software packages 

### High level optimal control modeling languages

- Pyomo with .DAE extension
- Modelica with JModelica, Optimica, Dymola
- Yalmip
- CasADi
- OpenOCL
- ICLOCS2 
- Acado
- CVX
- PSOPT
- BOCOP 
- GPOPS2
- ADRL Control toolbox 
- ADRL towr
- PROPT (commercial)
- DIDO (commercial)
- COMSOL (commercial)
- gPROMS (commercial)
- Forces (commercial)
- AMPL with TACO extension (commercial)
- Mujoco (commercial)

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
- CPLEX (commercial)
- Gruobi (commercial)
- MINOS (commercial)

#### Integer, mixed-integer programming

- Bonmin

## Automatic differentiation

- CasADi [[github](https://github.com/casadi/casadi)] [[web](https://web.casadi.org/)]
- JuliaDiff [[github](https://github.com/JuliaDiff/)] [[web](http://www.juliadiff.org/)]
- CppAD [[github](https://github.com/coin-or/CppAD)]
- CppADCodeGen [[github](https://github.com/joaoleal/CppADCodeGen)]


## Other material

- Summer School on Numerical Optimization Software, Hans D. Mittelmann, Moritz Diehl [[web](https://www.syscop.de/teaching/2016/summer-school-on-numerical-optimization-software)] [[repository](https://gitlab.syscop.de/teaching/NOS_public)]
- Decision tree, benchmarks for numerical optimization software, Hans D. Mittelmann [[web](http://plato.asu.edu/)]
