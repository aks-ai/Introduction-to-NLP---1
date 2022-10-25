# Problem Set 2 Task 2

# Objective

The objectives of this study were:

1. Create a high performing LDA model (gensim) with 9 topics

2. Report on both two metrics for the later released test dataset, using gensim implementations of the metrics .
      
      2. a. Perplexity
      
      2. b. Coherence  
# Dataset

For this study, we used the Emails dataset, it can be seen by the name T2_train.csv in the folder.

It contains 3659 emails in the dataset, these does not include nested emails.

# Environment

This code has been wirtten in Python3 and it can run on the Research Computing environment of Rochester Institute of Technology.

The python packages and versions have been imported in the environment.

# Usage 

Files required to run this task are:
1. Task2.ipynb

    Notebook file where the task has been performed.
    
3. Task2_test.ipynb
  
    Notebook file to test the task after the testing data is given.

5. custom_log_ratio_measure.py

    File that calculates the custom Coherence score.
  
7. id2world.pkl
    
    Pickle file with the dictonary used for the task.
    
9. lda_model.pkl

    Pickle file with the model preloaded.

**The Run All option in the Research Computing Enviornment for Jupyter notebook can give you all the output.**

**Note: - We have generated the pickle file and kept in the same folder, as long it stays in the same folder it runs without any problem.**

# Testing

For testing the algorithm we have kept the test data set file name as 'T2_test.csv', and considered that the the path of test data set file is in the folder as the code.

# Output

After receiving the test file for this code from the instructor we will run that on our code and then generate a new output file with the outputs of the text and its predicted emotion.

We will generate seperate output file for Task 2 with the name T2_output.csv
