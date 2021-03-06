About
------

PolyNondom is a small tool that helps to enumerate and visualise
different sets of points, in particular, different subsets of
non-dominated points. It is not supposed to compete with proper solvers
for multi-criteria integer optimisation but to help in developing and
testing the latter. PolyNondom can be used to create and enumerate
multi-criteria assignment and cube instances and to visualise subsets
in objective space. The current supported subsets are:

- non-dominated points
- dominated points
- polynon-dominated points
- mononon-dominated points

Documentation
-------------

The documentation for PolyNondom
is [online available ](https://asbestian.github.io/PolyNondom/).

It can also be compiled offline in the `/doc` folder via `make html`
(provided that [sphinx](http://www.sphinx-doc.org/en/stable/) is
installed).

Example visualisations
---------

![points][nondom points]

![points][points]

![boxes][boxes]

[nondom points]: ./doc/source/nondom_points.png 

[points]: ./doc/source/points.png 

[boxes]: ./doc/source/boxes.png "Visualisation showing polynon-dominated points (in blue) and mononon-dominated points (in brown) as well as feasible rectangular boxes given by polynon-dominated points."


Usage and command line interface
--------------------------------

Please refer to the sections **Basic usage** and **Command Line
Interface** in the [documentation](https://asbestian.github.io/PolyNondom/).
