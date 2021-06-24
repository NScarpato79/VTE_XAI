# Migraine-SVMWithGroupKernel

## Dataset

The dataset is made up of **1039** examples. Each example is represented by a features vector. The information present in the dataset relates to the patient's clinical analyzes. The features are grouped by groups, each of which represents a category. 
There are 7 groups:

- Demografiche
- Caratteristiche Cliniche
- Terapia
- Sintomatologia 
- Caratteristiche molecolari
- Biochimica Clinica 
- Trigger

## Feature Engineering and NaN values handling

For each **categorical column** we tranform each value in it's integer representation **(ex. Male, Female --> 0, 1)**. There are many NaN values in the dataset, to fill these values we use the mean of the reference column.


## Features Groups

In order to create a features groups representation of our dataset for each group we created a vector that contained all features of that group. The vector that represents a single example is a vector of groups vectors.

![example](https://user-images.githubusercontent.com/33979978/110512379-6ee12300-8105-11eb-85b7-7794dd3f2bb2.png)


## SVM

## Group Kernel

## Results
 
