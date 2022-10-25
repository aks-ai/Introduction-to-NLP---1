# Problem Set 2 Task 1.1 & Task 1.2

# Introduction

"Virtual contacts are becoming an important element of our life, especially in the context of COVID-19."

We set out to solve the problem of text-based emotion recognition since understanding emotions in a text message or social media remark is particularly difficult. Aside from the increased use of emoji, there is always a degree of subjectivity in how sentences are altered like sarcasm, irony, etc. 

Social media analysis, emotional distress detection, and other applications are among those available.

# Objective

The objectives of this study were:

1. Use the dataset of text samples labeled using a large spectrum of emotions

2. Train text classification models using Machine Learning and NLP techniques

# Dataset

For this study, we used the GoEmotions dataset, it can be seen by the name T1_train.csv in the folder.

This dataset was built by a Google Research team and gathers 6532 Reddit english comments(considering only the provided dataenvironmentset for this task). In fact, it is the largest manually labeled dataset in this topic as the complete dataset contains more than 58k comments.

However, this dataset presents several challenges:

**Very high number of emotions to detect**: 9 emotions + "neutral"

**Class imbalance:** ~30% of "neutral" samples

**Multi-label:** each sample can be labeled with different (multiple) emotions

# Environment

This code has been wirtten in Python3 and it can run on the Research Computing environment of Rochester Institute of Technology.

The python packages and versions have been imported in the environment.

# Usage 

We have made two notebook files, one includes the **'neutral'** label and another without the **'neutral'** label.

1. Task_1-1.ipynb

  This task takes T1_train.csv as input and then applies Gradient Boosting algorithm for classification and considers the 'neutral' emotion label.

**The Run All option in the Research Computing Enviornment for Jupyter notebook can give you all the output.**


2. Task_1-2.ipynb

  This task takes T1_train.csv as input and then applies Gradient Boosting algorihtm for classification and  does not consider the 'neutral' emotion label.

**The Run All option in the Research Computing Enviornment for Jupyter notebook can give you all the output.**

**Note: - We have generated the pickle file and kept in the same folder, as long it stays in the same folder it runs without any problem.**

# Testing

For testing the algorithm we have kept the test data set file name as 'T1_test.csv', and considered that the the path of test data set file is in the folder as the code.

# Output

After receiving the test file for this code from the instructor we will run that on our code and then generate a new output file with the outputs of the text and its predicted emotion.

We will generate two seperate output files for Task 1.1 and Task 1.2 with the name T1-1_output.csv and T1-2_output.csv respectively.

# Refrences 

[1] GoEmotions: A Dataset of Fine-Grained Emotions. Dorottya Demszky, Dana Movshovitz-Attias, Jeongwoo Ko, Alan Cowen], Gaurav Nemade, Sujith Ravi. arXiv:2005.00547v2
