# Random Forest Text Classifier

Randon Forest Text Classifier is a working proof of concept that (Data Version Control)DVC by DVC.ai can be used alongside with Git to not only version large data files and directories, but to better organize projects and reproduce complete data workflows for data science and machine learning projects

## Description

Random Forest Classifier is a machine learning project that creates a model to be used in predicing if a text can be classified as a comment about the R language.

DVC is used to create a pipeline containing python scripts to prepare data, featurize it, train the random forest classifier model, visualize and log the evaluation metrics.

The input data is divided into test and training data, with 20% of the data used for test data.

The project uses the following technologies:

- Python
- Pandas for data manipulation
- Skit Learn
- DVC for data files versioning
- DVCLive for logging evaluation metrics
- Matplotlib for plotting metrics
