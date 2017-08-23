# Subdivision-of-Human-Substantia-Nigra
We investigated the anatomical and functional organization of the human substantia nigra (SN) using diffusion and functional MRI data from the Human Connectome Project.  A tripartite connectivity-based parcellation of SN was identified with a limbic, cognitive, motor arrangement. 

The first part of this toolbox includes the parcellation pipeline, which loads connectivity information from the probablistic tractography maps and calculates similarity of connectivity profiles between seed voxels and subdivides them into groups using clustering algrithms.

The second part illustrates how to calculate the maximum probability tractograms, which emphasizes the distinction in fiber pathways seeding from different subregions.

The third part calculates the association between brain activity or connectivity and behavioral performance using PLS (http://www.rotman-baycrest.on.ca/pls/), which identifies linear combinations of brain activity and behavioural measures that maximally covary with each other.  
