# About

## Please cite as:

D. Matthews, S. Kriegman, C. Cappelle and J. Bongard, "Word2vec to behavior: morphology facilitates the grounding of language in machines," 2019 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS), Macau, China, 2019.

# Install
## Simulation
1. Clone and Install [ParallelPy](https://github.com/davidmatthews1uvm/ParallelPy)
1. Clone and Install [EvoDevo](https://github.com/davidmatthews1uvm/EvoDevo)
1. Install scipy
1. cd into the Pyrosim subfolder and follow the README.md there for installation instructions for pyrosim.
1. [Download](https://www.dropbox.com/s/xk1wddthvb5yyht/w2vVectorSpace-google.db?dl=0) Word2Vec vector space Database and place in demos sub folder.

# Demo
1. cd into 2019-IROS/demos and run python demo.py <word (english)>

# Running Experiments
1. cd into 2019-IROS/experiments and run python job.py <SEED> <JOB_NAME>
1. This will create an evolutionary trial directory and store results in a sqlite3 database.
1. Plots can be created with the Analyze.ipynb jupyter notebook.
