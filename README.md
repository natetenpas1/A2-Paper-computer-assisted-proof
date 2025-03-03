# A2-Paper-computer-assisted-proof
In this repository, you can find mathematica files which rigorously verify inequalities from the following 2 papers:
https://arxiv.org/abs/2307.15822<br />
https://arxiv.org/abs/2311.05594<br />

The first paper is joint work of mine with Doug Hardin, and the second is just me. The 2 papers focus on an important open problem in the mathematical study of point configurations,
called the "universal optimality of the hexagonal lattice." More can be found about the problem on my website on https://sites.google.com/view/nathanieltenpasmath/home .
<br />
The big open problem is to show that a particular distribution of points in the plane, called the hexagonal lattice, is "best" among all distributions of points in the plane. 
Of course, the full problem rigorously specifies what is meant by "best." In our work, we use a variation of the linear programming method
to show that the hexagonal lattice is best among a narrower distribution of points
(not precluding the possibility that the full generalization holds, which is in fact almost certainly true). We are hopeful that this method can be generalized someday 
to solve the full problem. In their original statement of the problem, Cohn and Kumar conjectured that the linear programming method could be used to solve it.  

The work of the mathematica notebooks is to first define truncations of theta functions on which we have rigorous error bounds. In the paper, we show various inequalities of the form F-G>=0 must hold on compact intervals, where F and G are both increasing. Those inequalities are handled rigorously in the notebooks using Mathematica's built-in interval arithmetic and the truncations mentioned above, along with a couple modules we create. 

software and skills: mathematica, interval arithmetic, computer assisted verification
