# barnes_hut_julia
This notebook demonstrates an implementation of the Barnes Hut algorithm in Julia, originally done for 18-335 at MIT.

You can read the accompanying paper [Octrees Quadtrees Barnes-Hut](https://github.com/linamaria11/barnes_hut_julia/blob/main/Octrees_Quadtrees_BarnesHut_explanation.pdf) for a bit on the implementation and references. 
The paper surveys the use of Octrees and Quadtrees. Special emphasis is given
to the implementation of the Barnes-Hut algorithm and it’s use of trees for n-body simulations.
Implementation of this is done in Julia code, using Quadtrees


The function create_bodies is modeled after the explanation provided by Frans Pretorius and Tim Koby. It uses the plummer model to create a toy universe, this model is denser at the center. https://physics.princeton.edu/~fpretori/Nbody/
