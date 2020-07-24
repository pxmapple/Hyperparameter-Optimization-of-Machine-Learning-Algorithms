# Hyperparameter Optimization of Machine Learning Algorithms

This code provides a hyper-parameter optimization implementation for machine learning algorithms, as described in the paper "On Hyperparameter Optimization of Machine Learning Algorithms: Theory and Practice".  

To fit a machine learning model into different problems, its hyper-parameters must be tuned. Selecting the best hyper-parameter configuration for machine learning models has a direct impact on the model's performance. In this paper, optimizing the hyper-parameters of common machine learning models is studied. We introduce several state-of-the-art optimization techniques and discuss how to apply them to machine learning algorithms. Many available libraries and frameworks developed for hyper-parameter optimization problems are provided, and some open challenges of hyper-parameter optimization research are also discussed in this paper. Moreover, experiments are conducted on benchmark datasets to compare the performance of different optimization methods and provide practical examples of hyper-parameter optimization.  

This paper and code will help industrial users, data analysts, and researchers to better develop machine learning models by identifying the proper hyper-parameter configurations effectively.

## Paper
[On Hyperparameter Optimization of Machine Learning Algorithms: Theory and Practice](https://www.google.ca/) 
### Quick Navigation
**Section 3**: Common hyper-parameters of machine learning algorithms  
**Section 4**: Hyper-parameter optimization techniques introduction  
**Section 5**: How to choose optimization techniques for different machine learning models  
**Section 6**: Common Python libraries/tools  
**Section 7**: Experimental results (sample code in "HPO_Regression.ipynb" and "HPO_Classification.ipynb")  
**Section 8**: Open challenges and future research directions  
**Summary table for Sections 3-6**: Table 2:  A comprehensive overview of common ML models, their hyper-parameters, suit-able optimization techniques, and available Python libraries  
**Summary table for Sections 8**: Table 10:  The open challenges and future directions of HPO research  

## Implementation
Sample code for hyper-parameter optimization implementation for machine learning algorithms is provided in this repository.  

### Sample code for Regression problems  
[HPO_Regression.ipynb](https://github.com/LiYangHart/Hyperparameter-Optimization-of-Machine-Learning-Algorithms/blob/master/HPO_Regression.ipynb)   
**Dataset used:** [Boston-Housing](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_boston.html)   
### Sample code for Classification problems  
[HPO_Classification.ipynb](https://github.com/LiYangHart/Hyperparameter-Optimization-of-Machine-Learning-Algorithms/blob/master/HPO_Classification.ipynb)   
**Dataset used:** [MNIST](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_digits.html#sklearn.datasets.load_digits)   

### Machine Learning Algorithms  
* Random forest (RF)
* Support vector machine (SVM)
* K-nearest neighbor (KNN)  

### HPO Algorithms  
* Grid search
* Random search
* Hyperband
* Bayesian Optimization with Gaussian Processes (BO-GP)
* Bayesian Optimization with Tree-structured Parzen Estimator (BO-TPE)
* Particle swarm optimization (PSO)
* Genetic algorithm (GA).  

### Requirements  
* Python 3.5  
* [scikit-learn](https://scikit-learn.org/stable/)  
* [hyperband](https://github.com/thuijskens/scikit-hyperband)  
* [scikit-optimize](https://github.com/scikit-optimize/scikit-optimize)  
* [hyperopt](https://github.com/hyperopt/hyperopt)  
* [optunity](https://github.com/claesenm/optunity)  
* [DEAP](https://github.com/DEAP/deap)  
* [TPOT](https://github.com/EpistasisLab/tpot)  

## Citation
If you find this repository useful in your research, please cite:  

L. Yang and A. Shami, "On Hyperparameter Optimization of Machine Learning Algorithms: Theory and Practice," Neurocomputing, 2020.
