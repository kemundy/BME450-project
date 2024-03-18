# BME 450 Final Project
## Title
Prediction of Breast Cancer Stage from Transcriptomic Data

## Team members
Kyle Mundy (kemundy), Jacob Nemivant (jnemivan)

## Project description
The dataset that we plan to use is from Kaggle, titled “Breast Cancer Gene Expression Profiles (METABRIC)”, with data that originally came from the Cambridge Research Institute and the British Columbia Cancer Centre. The dataset was uploaded to Kaggle in 2020 and has 1904 samples of patients with breast cancer (https://www.kaggle.com/datasets/raghadalharbi/breast-cancer-gene-expression-profiles-metabric?resource=download). Within each patient sample, there are many categories of useful information, like age, cancer type, treatment, different pathologies, size, cancer stage, and more. Additionally, the gene expression profile for each patient with 331 genes is provided, already normalized according to z-score normalization. The important data that will be drawn for this project will focus on the gene expression for the 331 genes, used to predict the cancer stage for the patients. The overall goal of the project is to build an efficient machine learning model that takes a gene expression profile of 331 different genes as input and predicts which stage of breast cancer that specific patient is at. This ranges from stage 1-4, while there are some samples that did not have a stage assigned, which will be dropped from the dataset when fitting the model. In the end, certain genes that are more likely to be correlated with breast cancer Certain parameters that will be explored to improve the efficiency of the model are the layer input sizes, number of layers, dropout values, learning rate, and optimizer/loss functions.
