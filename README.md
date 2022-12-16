# opensourceSW_final


### What I do in my project
After training brain tumor photographic data taken with MRI, find a model that classifies them.
We need to find the best model with the highest classification accuracy possible.

<br>

### The training dataset
brain tumor data in MRI

<br>

### The algorithm I choose
I chose Gaussian process classification (GPC) in Scikit-Learn

<br>

### parameter of the function
- kernel
- optimizer
- n_restarts_optimizer
- max_iter_predict
- warm_start
- copy_X_train
- random_state
- multi_class
- n_jobs
- 
<br>

### Configuration instructions
1. Load Packages
2. Load Additional Packages
3. Load Data Points
4. Classification with Scikit Learn Library
    - Find the best model and hyperparameter
    - Print accuracy
    - 
<br>

### Operating instructions
Gaussian process classification (GPC) based on Laplace approximation.
Internally, the Laplace approximation is used for approximating the non-Gaussian posterior by a Gaussian.
Currently, the implementation is restricted to using the logistic link function. For multi-class classification, several binary one-versus rest classifiers are fitted. Note that this class thus does not implement a true multi-class Laplace approximation.
<br>
(From https://scikit-learn.org/stable/modules/generated/sklearn.gaussian_process.GaussianProcessClassifier.html)

<br>

### Copyright and licensing information
https://github.com/scikit-learn/scikit-learn/blob/main/COPYING

<br>

### Contact information for the distributor or author
https://github.com/scikit-learn/scikit-learn
