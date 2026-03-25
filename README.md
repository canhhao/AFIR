# AFIR
Predicting reaction yields from Artificial Force Induced Reaction (AFIR) using graph-based methods


Data from: https://github.com/takahiro-doba-research/maeda-lab-postdoc

Experimenting with graph-based methods: 
1. Maxflow, mincut: not seem to correlate well with label, maybe the flows on the graph do not have bottleneck.
2. Hitting times: seems to be able to separate the low yields from high ones, but it alone doesn't predict well the label.
3. Edge features, the lowest rmse prediction so far.



The following image shows edge feature weights

Graph weights: <img src="https://github.com/canhhao/AFIR/blob/main/graphweights.png" alt="Graph and weights for reactions yield prediction" width="500"/>


Graph weights are to be tuned to reflect better the nature of chemical reactions! Currently a bit naive.
