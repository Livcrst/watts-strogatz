# Creating small world networks in Python using the Watts-Strogatz model
![Watts, D. J.; Strogatz, S. H. (1998). "Collective dynamics of 'small-world' networks" Nature. 393 (6684): 440–442.](https://github.com/sleepokay/watts-strogatz/blob/master/media/intro.png)

This is a Python implementation of the Watts-Strogatz model for generating small-world networks. GraphTest.py produces a .csv file which can be plotted to verify the result of [the 1998 paper](https://github.com/sleepokay/watts-strogatz/blob/master/references/watts%20%26%20strogatz%20-%20collective%20dynamics%20of%20small-world%20networks.pdf) by Duncan Watts and Steven Strogatz.

Graphs with small-world properties are characterized by short average path lengths and high clustering. They notably resemble many real-world phenomena such as food chains, electric power grids, brain neurons, voter networks, telephone call graphs, and social networks. The Watts-Strogatz model is a generative model which starts with a regular graph and rewires its edges randomly to produce graphs with small-world properties.

Below is a plot of the clustering coefficient and average path length against the rewiring probability _p_. The plot from the Watts and Strogatz paper is included below for reference.

![From this implementation](https://github.com/sleepokay/watts-strogatz/blob/master/media/plot.png)
![From the paper by Watts & Strogatz](https://github.com/sleepokay/watts-strogatz/blob/master/media/ws.png)