This is the repository containing the code for the paper titled "Rare and Different: Anomaly Scores from acombination of likelihood and out-of-distributionmodels to detect new physics at the LHC"

There are a few notebooks that each do a separate thing.

- deepsvdd.ipynb will run train the SVDD networks
- combine-svdd-into-ensemble.ipynb will merge the individual SVDD networks into a SVDD ensemble
- flow.ipynb will train the autoregressive flow network
- combined-svdd-ensemble-flow.ipynb will combine the ensemble of SVDD networks and flow model

The dataset used is the one from the Darkmachines Unsupervised challenge, which can be found here: https://zenodo.org/record/3961917. A PDF describing the dataset is also found there.
