# Migraine-SVMWithGroupKernel

## Dataset

VTE validation dataset, refer to Validation of a machine learning approach for venous thromboembolism risk prediction in oncology Desease Marker 2017

## Feature Engineering and NaN values handling

For each **categorical column** we tranform each value in it's integer representation **(ex. Male, Female --> 0, 1)**. There are many NaN values in the dataset, to fill these values we use the mean of the reference column.


## Features Groups

In order to create a features groups representation of our dataset for each group we created a vector that contained all features of that group. The vector that represents a single example is a vector of groups vectors.




## SVM

## Group Kernel

## Results
 
