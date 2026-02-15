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
   * [slides 0: Hands-off introduction to ML](slides/0.introduction_to_machine_learning.pdf) (Filippo)
* Model and variable selection: the machine learning paradigm
   * [slides 1.variable_selection](slides/1.variable_selection.pdf)  (Filippo)
* Introduction to advanced R data libraries [Rmd](scripts/R_advanced_libraries.Rmd)
* Multivariate data: things to always remember
    * [Omics meet ML](slides/omics_meet_ML.pdf) (Pietro) 


**Day 2**

* Introduction to `tidymodels` [Rmd](scripts/Introduction_to_tidymodels.Rmd)
    * [data_athletes](data/athlete_events.csv)
* Supervised learning: regression and classification
   * [slides 2.Supervised learning](slides/2.supervised_learning.pdf)  (Filippo) 
   * [script 1.introduction_to_ml] [(.Rmd)](scripts/1.introduction_to_ml.Rmd) <!-- [(ipynb)](scripts/1.introduction_to_ml.ipynb) -->
 * Machine learning for regression problems
   * [data_reg](data/DNA methylation data.xlsm)
   * [slides 3.Regression](slides/3.regression.pdf) (Filippo)
   * [script 2.linear_regression] [(.Rmd)](scripts/2.linear_regression.Rmd) <!-- [(ipynb)](scripts/2.linear_regression.ipynb) -->

**Day 3**

* Overfitting and resampling techniques
   * [script 3.training_testing] [(.Rmd)](scripts/3.training_testing.Rmd) <!-- [(ipynb)](scripts/3.training_testing.ipynb) -->
   * [slides 4.overfitting](slides/4.overfitting.pdf) (Filippo)
   * [slides 5.resampling](slides/5.resampling.pdf) (Filippo)
* Classification problems
   * [data_class](data/dogs_imputed_reduced.raw) 
   * [script 4.classification] [(.Rmd)](scripts/4.classification.Rmd) <!-- [(ipynb)](scripts/4.classification.ipynb) -->
   * [slides 6.classification](slides/6.classification.pdf) (Filippo)
* Regression and classification with tidymodels
   * [script 5.regression_and_classification_with_tidymodels] [(.Rmd)](scripts/5.regression_classification_tidymodels.Rmd) <!-- [(ipynb)](scripts/5.regression_classification_tidymodels.ipynb) -->
   * [script 5.2 Snippet on model complexity] [(.Rmd)](scripts/5.2.model_complexity.Rmd) 
   * [script 5.3 Snippet on finetuning the model complexity hyperparameter] [(.Rmd)](scripts/5.3.tuning_complexity.Rmd)
* Unsupervised learning: PCA, Umap, Self-organizing maps (Pietro) 
   * PCA demo [(.Rmd)](scripts/PCA_with_tidymodels.Rmd)
* Unsupervised learning demos
   * UMAP demo [(.Rmd)](scripts/UMAP_with_tidymodels.Rmd)
   * SOM demo [(.Rmd)](scripts/SOMs_also_with_tidymodels.Rmd)

**Day 4**

* Lasso-penalised linear and logistic regression
   * [data_lasso](data/dogs_imputed.raw) 
   * [script 6.lasso] [(.Rmd)](scripts/6.lasso.Rmd) <!-- [(ipynb)](scripts/6.lasso.ipynb) -->
   * [slides 7.lasso_regularization](slides/7.lasso_regularization.pdf) (Filippo)
* Lasso and model tuning
   * [data lasso 2](data/MTBSL1.tsv)
   * [script 7.lasso_with_tidymodels] [(.Rmd)](scripts/7.lasso_with_tidymodels.Rmd) <!-- [(ipynb)](scripts/7.lasso_with_tidymodels.ipynb) -->
* Random Forest for regression and classification
   * [script 8.random_forest] [(.Rmd)](scripts/8.random_forest.Rmd) <!-- [(ipynb)](scripts/8.random_forest.ipynb) -->
   * [script 9.multiclass_random_forest] [(.Rmd)](scripts/9.multiclass_random_forest.Rmd) <!-- [(ipynb)](scripts/9.multiclass_random_forest.ipynb) -->
   * [slides 8.random_forest](slides/8.random_forest.pdf) (Filippo)
* KNN imputation [optional]
   * [script knni] [(.Rmd)](scripts/knni.Rmd) <!-- [(ipynb)](scripts/knni.ipynb) -->

**Day 5**

* Slow learning: the boosting approach [optional]
   * [script 10.boosting] [(.Rmd)](scripts/10.boosting.Rmd) <!-- [(ipynb)](scripts/10.boosting.ipynb) -->
   * [slides 9.boosting](slides/9.boosting.pdf) (Filippo)
* SVM demo [(.Rmd)](scripts/svm_snippet.Rmd) [optional]
* One-class classification (SVM inside) [.Rmd](scripts/one-class_snippet.Rmd) [optional]
* Datasets
   * [dataset 1 (rubus)](data/rubusTable.txt) [dataset 3 (komp reduced)](data/KOMP_data_targeted.RData)
* Final interactive exercise: [(.Rmd)](scripts/final_exercise.Rmd)
* Wrap-up **quiz**: let’s test our machine learning skills!
   * [Go to test!](https://docs.google.com/forms/d/e/1FAIpQLSd6pqcn6I_X3Ag1jq_sPcRbOnbJXMnXRa2cgxgCxYMLiNspwA/viewform?usp=sharing) 
* Q&A

**R Libraries**

* Complete list [here](https://github.com/pietrofranceschi/Physalia_ML/blob/main/r_packages.R)

## Timetable
[timetable](https://docs.google.com/spreadsheets/d/1KJlq50n6D_TxiQWGZhsVhJVmQWgiPh37WoBmexnMT1k/edit?usp=sharing)



