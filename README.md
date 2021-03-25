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
* More on advanced data libraries: `tidymodels`[Rmd](scripts/tidymodels.Rmd)
* Supervised learning: regression and classification
   * [script 1.introduction_to_ml] [(.Rmd)](scripts/1.introduction_to_ml.Rmd) [(html)](scripts/1.introduction_to_ml.html) [(ipynb)](scripts/1.introduction_to_ml.ipynb) 
   * [slides 1.Supervised learning](slides/1.supervised_learning.pdf)  (Filippo) 

**Day 3**
* Machine learning for regression problems
   * [data_reg](data/DNA methylation data.xlsm)
   * [script 2.linear_regression] [(.Rmd)](scripts/2.linear_regression.Rmd) [(html)](scripts/2.linear_regression.html) [(ipynb)](scripts/2.linear_regression.ipynb) 
   * [slides 2.Regression](slides/2.regression.pdf) (Filippo)
* Overfitting and resampling techniques
   * [script 3.training_testing] [(.Rmd)](scripts/3.training_testing.Rmd) [(html)](scripts/3.training_testing.html) [(ipynb)](scripts/3.training_testing.ipynb)
   * [slides 3.overfitting](slides/3.overfitting.pdf) (Filippo)
   * [slides 4.resampling](slides/4.resampling.pdf) (Filippo)
* Classification problems
   * [data_class](data/dogs_imputed_reduced.raw) 
   * [script 4.classification] [(.Rmd)](scripts/4.classification.Rmd) [(html)](scripts/4.classification.html) [(ipynb)](scripts/4.classification.ipynb)
   * [slides 5.classification](slides/5.classification.pdf) (Filippo)
* Lasso-penalised linear and logistic regression
   * [data_lasso](data/dogs_imputed.raw) 
   * [script 5.lasso] [(.Rmd)](scripts/5.lasso.Rmd) [(html)](scripts/5.lasso.html) [(ipynb)](scripts/5.lasso.ipynb)
   * [slides 6.lasso_regularization]
* KNN imputation
   * [script knni] [(.Rmd)](scripts/knni.Rmd) [(html)](scripts/knni.html) [(ipynb)](scripts/knni.ipynb)

**Day 4**
* Lasso and model tuning
   * [data lasso 2]
   * [script 6.lasso_with_tidymodels]
* Random Forest for regression and classification
   * [script 7.random_forest]
   * [script 8.multiclass_random_forest]
   * [slides 7.random_forest] 
* Slow learning: the boosting approach
   * [script 9.boosting]
   * [slides 8.boosting]
* Advanced data visualization - part 1 

**Day 5**
* Data visualization: master ggplot!
* Final interactive exercise
* Model and variable selection: the machine learning paradigm
* Kahoot quiz: let’s test our machine learning skills!
* Q&A

**R Libraries**
* Complete list [here](https://github.com/pietrofranceschi/Physalia_ML/blob/main/r_packages.R)

## Timetable
[timetable](https://docs.google.com/spreadsheets/d/1KJlq50n6D_TxiQWGZhsVhJVmQWgiPh37WoBmexnMT1k/edit?usp=sharing)



