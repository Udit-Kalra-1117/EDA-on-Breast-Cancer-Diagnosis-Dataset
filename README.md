# EDA-on-Breast-Cancer-Diagnosis-Dataset

This repository contains the Exploratory Data Analysis on Breast Cancer Wisconsin (Diagnostic) Data Set.
For this i used the pandas library along with seaborn library.
Throughout the process I used various types of plots like count plot, violin plots, box plots, joint plots and swarm plots.
Also, plotted a heatmap for each pair of columns in the dataset.


The most useful column of the dataset is "Diagnosis" and the "ID" & the "Unnamed: 32" columns are not useful for EDA.


The EDA is divide into 8 steps viz:

Step 1: The required libraries and the required data set is loaded.

Step 2: The 3 columns: ID, Unnamed: 32 and Diagnosis are dropped.

Step 3: The count of entries of Benign Tumors and Malignant Tumors is shown using count plot.

Step 4: Violin plot of the first 10 columns of 30 is obtained.

Step 5: Violin plot of the remaining 20 columns is obtained in the sets of 10 10 columns each (11-20 and 21-30) and a box plot is also obtained to observe the correlation of Benign Tumors and Malignant Tumors properly.

Step 6: As from Violin plot we can see that columns "concavity_worst" and "concave points_worst" almost produce the same output so using a joint plot we compare these two columns and plot a regression joint plot

Step 7: Swarm plots are plotted to observe the distribution of the values and their variances in 3 sets of 10 columns each(1-10, 11-20 and 21-30).

Step 8: Plotting a Heatmap pairing all the columns of the dataset.
