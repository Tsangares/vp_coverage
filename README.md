# Vietoris–Rips Coverage

A point $x \in U$ is VR-covered if it is contained in a triangle spanned by three sensors that lie pairwise within distance $R$ of each other.

It is a theorem that VR-coverage implies r-coverage. This follows from the trigonometric result that if the three sides of a triangle have length at most $R$ then the three disks of radius $R/\sqrt{3}$ centered at the vertices cover the entire triangle. (The ratio $1/\sqrt{3}$ cannot be made smaller: consider an equilateral triangle.)

# In this repo
There is a file `topology.ipynb` that uses [QR-Decomposition and backsubstiution](https://inst.eecs.berkeley.edu/~ee127/sp21/livebook/l_lineqs_solving.html) to solve the space of 2-cycles (simplex/triangles) in seach for a solution of 2-cycles that all connect the boundary. 
