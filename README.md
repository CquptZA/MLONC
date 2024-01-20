# MLONC
The code of Oversampling Multi-Label Data based on Natural Neighbor and Label Correlation:
step:

1.pip install skmultilearn or move skmultilearn we provide in your conda env (I suggest moving the package we provide directly,because the original package had many bugs).

skmultilearn provides many classic MLC algorithms, such as BR, CC, RAKEL, and MLkNN, etc. but unfortunately, it is no longer maintained and we have fixed bugs in these algorithms. More details http://scikit.ml/.

2.run MLNONC.ipynb You can adjust the sampling rate from the "main" function.
The code of MLONC is mainly divided into three parts: 

data processing (Each function is easy to understand)
our main method (searching for natural neighbors and sampling)
training(5 * 2 fold cross validation)



main package version:

numpy                              1.21.6 

pandas                             0.24.2 

scikit-learn                       1.0.2   

scikit-multilearn                  0.2.0  

and python==3.7



We have provided Macro-F for evaluation metrics, and more evaluation metrics can be easily added by yourselves. Of course, we will provide all parameter values after the paper is accepted.
