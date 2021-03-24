# Physalia_ML


**Machine Learning for Biologists, a hands-on introduction**

Instructors: *Pietro Franceschi, Filippo Biscarini*

Synopsis
The use of modern quantitative technologies to characterize complex phenomena represents the standard approach in almost every research domain. Biology makes no exception and the use of multi-omics techniques (metabolomics, transcriptomics, genomics and proteomics) is pervasive in every facet of life sciences. The resulting multivariate datasets are highly complex and advanced data analysis approaches need to be applied to optimize the information retrieved. For relatively large-scale studies, machine learning represents a valid tool to complement classical multivariate statistical methods.
The objective of this course is to highlight advantages and limitations of these data analysis approaches in the context of biological research, providing a broad hands-on introduction to the use of multivariate methods and machine learning for the analysis of ‘omics datasets.

Below the structure of the course, and a detailed timetable (link at the end of the document).
Code and data will be available at the beginning of each day. Slides will be available at the end of each day.


**Day 1**

* General Introduction 
* Data mining, -omics and machine learning
    * [slides 0.Introduction to ML](slides/0.introduction_to_machine_learning.pdf) (Filippo) 
    * [Omics meet ML](slides/Omics_meet_ML.pdf) (Pietro) 
* Introduction to advanced R data libraries [Rmd](scripts/Day_1.Rmd)

**Day 2**
* More on advanced data libraries: `tidymodels`
* Multivariate data: Generalities
* Unsupervised statistical problems
* Principal Component Analysis & Beyond
* PCA as a data model, introduction to validation
* Supervised learning: regression and classification
   * [script 1.introduction_to_ml.Rmd](scripts/1.introduction_to_ml.Rmd) [(html)](scripts/1.introduction_to_ml.html) [(ipynb)](scripts/1.introduction_to_ml.ipynb) 
   * [slides 1.Supervised learning](slides/1.supervised_learning.pdf)  (Filippo) 

**Day 3**
* Machine learning for regression problems
   * [data_reg](data/DNA methylation data.xlsm)
   * [script 2.linear_regression](scripts/2.linear_regression.Rmd) [(html)](scripts/2.linear_regression.html) [(ipynb)](scripts/2.linear_regression.ipynb) 
   * [slides 2.Regression] (Filippo)
* Overfitting and resampling techniques
   * [script 3.training_testing.Rmd]
   * [slides 3.overfitting]
   * [slides 4.resampling]     
* Classification problems
   * [data_class](data/dogs_imputed_reduced.raw) 
   * [script 4.classification.Rmd]
   * [slides 5.classification]
* Lasso-penalised linear and logistic regression
   * [data_lasso](data/dogs_imputed.raw) 
   * [script 5.lasso.Rmd]
   * [slides 6.lasso_regularization]
* KNN imputation
   * [script knni.Rmd] 

**Day 4**
* Lasso and model tuning
* Random Forest for regression and classification
* Slow learning: the boosting approach

**Day 5**
* Data visualization: master ggplot!
* Model and variable selection: the machine learning paradigm
* Kahoot quiz: let’s test our machine learning skills!
* Q&A

**R Libraries**
* Complete list [here](https://github.com/pietrofranceschi/Physalia_ML/blob/main/r_packages.R)

## Timetable
[timetable](https://docs.google.com/spreadsheets/d/1KJlq50n6D_TxiQWGZhsVhJVmQWgiPh37WoBmexnMT1k/edit?usp=sharing)



