# Random-Forest-Classifier
Random Forest is a supervised machine learning algorithm which is based on ensemble learning. In this project, we build three Random Forest Classifier models to predict ICI response based on 55,292, 5,761, and 3,522 differentially abundant genes, respectively. This repository provides the source code for three Random Forest (RF) classifiers and other comparative machine learning algorithms, along with the feature matrix and sample classification label files used for training and testing.
## Types of files
This repository contains the following four major types of files:
1. **RF_55292_features.ipynb**: Jupyter notebook containing the implementation of the Random Forest classifier for 55,292 features. Notes: SVC, Support Vector Classification; KNN, k-nearest neighbors classifier; DT, Decision Tree classifier; LR, Logistic Regression classifier; HGB, Histogram-based Gradient Boosting Classification Tree.
2. **label_755.txt and label_64.txt**: Text files providing the sample classification labels for the training cohort (755 samples) and validation cohort (64 samples), respectively.
3. **difgene_abundance_755_5761_train.txt**: The feature matrix for the training cohort, containing 5,761 features across 755 samples.
4. **difgene_abundance_64_5761_test.txt**: The feature matrix for the validation cohort, containing 5,761 features across 64 samples.
## Note
Due to GitHub's 25 MB file size limit, large matrix files have been split into smaller parts and compressed for upload. 
### Decompression Instructions
```
cat difgene_abundance_755_55292_train.tar.gz* |tar zx
```
