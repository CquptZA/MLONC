# MLONC
The code of Oversampling Multi-Label Data based on Natural Neighbor and Label Correlation:
step:

1.pip install skmultilearn or move skmultilearn we provide in your conda env (I suggest moving the package we provide directly,because the original package had many bugs).

2.run MLNONC.ipynb You can adjust the sampling rate from the "main" function.
The code of MLONC is mainly divided into three parts: 

data processing (Each function is easy to understand)
our main method (searching for natural neighbors and sampling)
training(5 * 2 fold cross validation)

More base classifiers and data acquisition methods http://scikit.ml/

main package version:

numpy                              1.21.6 

pandas                             0.24.2 

scikit-learn                       1.0.2   

scikit-multilearn                  0.2.0  

and python==3.7

Here we only provide evaluation metrics for Macro-F，You can implement more evaluation methods yourself

We will announce all sampling parameter settings after the paper is accepted
