# Particle Detection
 
This program uses a neural network to identify the signal of a particle with unknown mass, for use in particle accelerators. 

There are 3 datasets: the first contains samples of only particles with mass 1000 GeV, the second contains samples of particles with mass points of around but not including 1000 (masses are 500,750,1250,1500), while the third dataset contains samples of particles at all mass points (500,750,1000,1250,1500). The goal was to be able to find a particle's signal of a certain mass, without being trained on samples of that mass (i.e. finding a 1000 GeV particle without seeing samples of masses with 1000 GeV).


Dataset came from UC Irvine's Machine Learning Repository

Relevant paper:
Pierre Baldi, Kyle Cranmer, Taylor Faucett, Peter Sadowski, and Daniel Whiteson. 'Parameterized Machine Learning for High-Energy Physics.' www.doi.org/10.1140/epjc/s10052-016-4099-4.
