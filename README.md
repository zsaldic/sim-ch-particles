# Simulation of Charged Particle Multiplicity Distributions
***
## Introduction
This program is a toy model that simulates the creation of particles as a result of nuclei collisions. The code uses calculations from a [_Glauber model_ ](https://cholmcc.gitlab.io/nbi-python/mechanics/index.da.html#Glauber) to produce charged particles.
The general workflow of the program is as follows:

* Compute 
* Distribute
* Vizualize 

First, it computes the number (multiplicity) of charged particles by combining an _ancestor model_ with a _particle production model_. Next, it distributes the particles spatially in proper coordinates (η,φ) (pseudorapidity and azimuthals). Lastly, it visualizes the particle hits.

## Usage
The code is run on a [Jupyter Notebook](https://jupyter.org/). It requires the [`nbi_stat`](https://pypi.org/project/nbi-stat/) module (statistical tools used for teaching at Niels Bohr Insitute (NBI), written by _Christian Holm Christensen_).

A data sample (100 events) is provided and located in `/data` folder. To sample more data, follow the instructions of the [Glauber model](https://cholmcc.gitlab.io/nbi-python/mechanics/index.da.html#Glauber).  
***
© 2020 Zlatko Šaldić


