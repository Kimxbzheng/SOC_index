# iPAGE v2.0
This code is used to extract reversal pairs intra- and inter-samples.

*main.ipynb* contains the whole process.

*pairmodule.py* contains the core modules that implements the reversal extraction, reversal comparison. If you want to apply iPAGE, you can just take this part into your code.

*num_cmRNA0.5.txt* contains the circRNAs and mRNAs interaction in the ceRNA network.

*num_lmRNA0.5.txt* contains the lncRNAs and mRNAs interaction in the ceRNA network.


## Dependency
numpy, scipy, matplotlib, statsmodels, fisher, sklearn, seaborn, pandas, mpl_toolkits, imblearn, mlxtend

## Data
We provided our data in our paper. The other datasets can be inferred from the paper and downloaded from GEO.
