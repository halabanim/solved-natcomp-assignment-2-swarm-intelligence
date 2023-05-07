Download Link: https://assignmentchef.com/product/solved-natcomp-assignment-2-swarm-intelligence
<br>



<ol>

 <li>(PSO)  Suppose you want to use a PSO system to maximize the function</li>

</ol>

<em>,</em>

where −500 ≤ <em>x</em>(<em>i</em>) ≤ 500. A graph of this function is shown in the slides of the lecture (the function’s global maximum is at <em>f</em>(<em>x</em>) = 837<em>.</em>9658 for <em>x</em>(<em>i</em>) = −420<em>.</em>9687, <em>i </em>= 1<em>,</em>2).

Consider an illustrative example of a PSO system for composed of three particles. The space of solutions is a two dimensional real valued space: −500 ≤ <em>x</em>(<em>i</em>) ≤ 500. Consider the update rule for each particle <em>i</em>:

<em>,</em>

where <em>x</em><sup>∗</sup><em><sub>i </sub></em>denotes the personal best and <em>x</em><sup>∗ </sup>the social (global) best. To facilitate calculation, for this exercise we will ignore the fact that <em>r</em><sub>1 </sub>and <em>r</em><sub>2 </sub>are random numbers and fix them to 0<em>.</em>5 and <em>α</em><sub>1 </sub>= <em>α</em><sub>2 </sub>= 1. Suppose the current state of the swarm is as follows.

<ul>

 <li>Position of particles: <em>x</em><sub>1 </sub>= (−400<em>,</em>−400); <em>x</em><sub>2 </sub>= (−410<em>,</em>−410); <em>x</em><sub>3 </sub>= (−415<em>,</em>−415);</li>

 <li>Individual best positions: ;</li>

 <li>Social best position: <em>x</em><sup>∗ </sup>= <em>x</em><sub>3</sub>; Velocities: <em>v</em><sub>1 </sub>= <em>v</em><sub>2 </sub>= <em>v</em><sub>3 </sub>= (−50<em>,</em>−50).</li>

 <li>Compute the fitness of each particle.</li>

 <li>What would be the next position and fitness of each particle after one iterationof the PSO algorithm, when using <em>ω </em>= 2, <em>ω </em>= 0<em>.</em>5, and <em>ω </em>= 0<em>.</em>1? (In case a component of a new position falls outside the range −500 ≤ <em>x</em>(<em>i</em>) ≤ 500, it is mapped to its closest value in the range. For instance, if the computation of new position gives (550<em>,</em>500), it is set to (500<em>,</em>500).) (c) Explain what is the effect of the parameter <em>ω</em>.</li>

</ul>

(d) Give an advantage and a disadvantage of a high value of <em>ω</em>.

<ol start="2">

 <li>(PSO) [2 points] Consider a particle “swarm” consisting of a single member. How would it perform in a trivial task such as the minimization of <em>f</em>(<em>x</em>) = <em>x</em><sup>2 </sup>when <em>ω &lt; </em>1, assuming the particle starts with the velocity pointing away from the optimum (e.g. in a state with velocity <em>v </em>= 10; position <em>x </em>= 20)?</li>

 <li>(PSO) [2 points] Implement the PSO algorithm for clustering described in “Van der Merwe, D. W., and Andries Petrus Engelbrecht. ”Data clustering using particle swarm optimization.” Evolutionary Computation, 2003. CEC’03. The 2003 Congress on. Vol. 1. IEEE, 2003.” (see also swarm intelligence slides). Implement the k-means clustering.</li>

</ol>

Apply and compare the performance of the two algorithms in terms of quantization error on Artificial dataset 1 and on the Iris dataset (the latter available at UCI

ML repository, see <a href="https://archive.ics.uci.edu/ml/datasets/iris">https://archive.ics.uci.edu/ml/datasets/iris</a><a href="https://archive.ics.uci.edu/ml/datasets/iris">)</a>. <em>In both algorithms, use the true number of clusters as value of the parameter for setting the number of clusters.</em>

<ol start="4">

 <li>(ACO)  Read the paper: Blum, Christian, and Marco Dorigo. ”Search bias in ant colony optimization: On the role of competition-balanced systems.” IEEE Transactions on Evolutionary Computation 9.2 (2005): 159-174. Figure 1 shows a (toy) problem instance for the 2-cardinality tree problem. The 2-cardinality tree problem amounts to finding a subtree <em>T </em>of a given undirected graph <em>G </em>with exactly 2 edges and the minimum possible weight.

  <ul>

   <li>Is ACO for this problem a Competition-Balanced System (CBS)? Justify youranswer. (A definition of CBS also given in the slides.)</li>

   <li>If a combination of an ACO algorithm and a problem instance is not a CBS, isthe induced bias always harmful? Justify your answer.</li>

  </ul></li>

</ol>

Figure 1: 2-cardinality problem instance

<ol start="5">

 <li>(ACO)  The figure below shows an example of an instance of a sourcedestination problem from the ACO book by Dorigo and Stuetzle. The goal is to reach the destination node from the source one using a shortest path through the given graph. What results do you expect for an ant colony algorithm that does not use tabu lists (except for inhibition of immediate return to the previous node)?</li>

</ol>