# AFIR
Predicting reaction yields from AFIR using graph-based methods


Data from: https://github.com/takahiro-doba-research/maeda-lab-postdoc

Experimenting with graph-based methods: 
1. Maxflow, mincut: not seem to correlate well with label, maybe the flows on the graph does not have bottleneck.
2. Hitting times: seems to be able to separate the low yields from high ones, but itself alone doesn't predict well.
3. Edge features:

Graph weights are to be tuned to reflect the nature of chemical reactions! Currently a bit naive.

The following image shows edge feature weights

Graph weights: <img src="https://github.com/canhhao/AFIR/blob/main/graphweights.png" alt="Graph and weights for reactions yield prediction" width="500"/>
