# Temporal-Motifs

The paper associated with this repo, "Temporal Motif Participation Profiles for Analyzing Node Similarity in Temporal Networks," presented at The 17th International Conference on Advances in Social Networks Analysis and Mining (ASONAM 2025), can be found here: https://arxiv.org/abs/2507.06465. 

#

The TMPP-Analysis directory contains the main files for analyzing TMPPs.
- MIDsPositioned.ipynb is the main (positioned) TMPP analysis file.
- MIDsPositionless.ipynb contains analysis for positionless TMPPs.
- simulate_mulch_scenario1.ipynb shows scenario 1 in Section 4.1 and Figure 3.
- simulate_mulch_scenario2.ipynb shows scenario 2 in Section 4.1 and Figure 4.
- TMPP_Toy_Example.ipynb shows the toy example in Section 3.1 and Figure 2.

The data subdirectory contains relevant data files.
- COW-country-codes.csv translates COW country code abbreviations into the countries' full names.
- graphs.pickle stores the MIDs graphs.

#

The MULCH and dynetworkx directories contain the correct versions of each library that are used in this project. Their repositories can be found here:
- https://github.com/IdeasLabUT/Multivariate-Community-Hawkes
- https://github.com/IdeasLabUT/dynetworkx
