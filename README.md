# Compressed Sensing - Semidefinite Relaxations for Integer Programming

This is the final project conducted by Rémy Deshayes and Eric Lavergne for the Compressed Sensing course.

Our project is based on the work of Franz Rendl in [Semidefinite Relaxations for Integer Programming](https://homepages.cwi.nl/~monique/ow-seminar-sdp/files/rendl_chapter.pdf).
We summarized the main ideas of the article and implemented some of the solutions described in the survey for the two classical problems of maxcut and graph coloring.

The first part 1. Approachs for Integer Programming quickly introduces the approaches used in this field.
The second part 2. The basics of Semi Definite Optimization outlines the main ideas of SDP programming.
The third part 3. Famous COP, SDP relaxation and hyperplane rounding considers the examples of two classical problems,
Max-Cut and Graph coloring, that can be solved thanks to SDP programming.
Once a solution of the SDP relaxation has been obtained, the hyperplane rounding algorithm is used to obtain a good solution in the initial space.
Finally, in the last part 4. Interior Points methods for SDP programming and more, we describe methods to compute SDP problems.
