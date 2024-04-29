##Network Intrusion Detection with PySpark
##Overview
This project focuses on network intrusion detection, leveraging PySpark to classify network traffic into normal and  different attacks categories. The main objective is to develop a machine learning model classifying network intrusions.


## Dataset
The dataset used for this project is the NSL-KDD dataset, which is a modified version of the original KDD Cup 1999 dataset. It consists of a large number of network connections categorized as normal or one of several attack types.
<a href="https://www.unb.ca/cic/datasets/nsl.html">link to dataset</a>

##Approach
The project utilizes a Jupyter Notebook (main_notebook.ipynb) with PySpark to perform the following tasks:

Data preprocessing and exploratory data analysis (EDA).
Feature engineering to extract relevant features from the dataset.
Model development and training using PySpark's MLlib library, employing supervised learning algorithms such as Support Vector Machine, Multi Layer Perceptron, and Random Forest.
Evaluation of model performance using various metrics, including accuracy, false negative rate, true positive rate, and confusion matrix analysis.
