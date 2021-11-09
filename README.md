# Entropy-and-Gini-index-based-Decision-tree

* Entropy
Entropy helps us to build an appropriate decision tree for selecting the best splitter. Entropy can be defined as a measure of the purity of the sub split. 
Entropy always lies between 0 to 1. The entropy of any split can be calculated by this formula. 

  $$ \left.\left.\left.H(s)=-P_{(}+\log _{2} P_{(}+\right)-P_{(}-\right) \log _{2} P_{(-}\right) $$ $\left.\operatorname{Here} P_{(}+\right) / P_{(-)}=\%$ of $+$ ve class $1 \%$ of - ve class

The algorithm calculates the entropy of each feature after every split and as the splitting continues on, it selects the best feature and starts splitting according to it.
