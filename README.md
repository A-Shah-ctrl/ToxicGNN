# ToxicGNN
A Graph Neural Network trained on Tox21 to identify where a compound (<= 100 atoms) will activate a Nuclear Response in Androgen Receptors (Graph Classification Task).

## Data
data.csv used is the same file as found on https://github.com/deepchem/deepchem/blob/master/datasets/tox21.csv.gz

## Variations
To train a model on other Nuclear Responses you simply need to change the classes variable in gen_graph.ipynb