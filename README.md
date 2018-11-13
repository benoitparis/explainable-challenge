## Explainable Machine Learning Challenge

This is my proposal for the [explainable.ml](http://explainable.ml) challenge organised by FICO, Google, NIPS.

[Here is the paper which details my approach](https://github.com/benoitparis/explainable-challenge/raw/master/Decision%20tree%20node%20participation%20as%20a%20tool%20for%20interpretability.pdf). 

The "Global interpretation - intuitive.ipynb" notebook in this repository contain an interactive visualization fit for fast intuitive data exploration.

The "RuleFitCustom - Global and Local explanations.ipynb" notebook contains local and global rules that are simpler than extracted from [standard RuleFit](https://statweb.stanford.edu/~jhf/R_RuleFit.html).

## Installation instructions

We recommend Python 3.7 and an environment with the following packages:

```
pandas matplotlib plotly ipython ipykernel
```

Installation of the customized implementation of RuleFit:

```
pip install -e ./rulefitcustom
```
