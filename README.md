# Supervised-Machine-Learning
- `Breast Cancer`(diagnostic)

This project is a supervised classification machine learning project to predict whether the cancer is benign or malignant. The data set used in this project is the Breast Cancer Wisconsin (Diagnostic) Data Set.

![alt text](https://github.com/yasmina-99/Supervised-Machine-Learning/blob/main/Standardization-of-H-E-stained-histopathology-image-appearance-A-Two-raw-images-with.png)


## About the Dataset
The dataset consists of features computed from a `digitized image of a fine needle aspirate (FNA) of a breast mass.` These features describe characteristics of the cell nuclei present in the image. The dataset contains 569 instances, each with 32 attributes. The first attribute is the ID number, the second is the diagnosis (M = malignant, B = benign), and the remaining 30 attributes are real-valued features computed for each `cell nucleus.`

## Attribute Information
ID number
`Diagnosis (M = malignant, B = benign)`
3-32. Ten real-valued features computed for each cell nucleus:
a. `radius` (mean of distances from center to points on the perimeter)
b. `texture` (standard deviation of gray-scale values)
c. `perimeter`
d. `area`
e. `smoothness` (local variation in radius lengths)
f. `compactness` (perimeter^2 / area - 1.0)
g. `concavity` (severity of concave portions of the contour)
h. `concave points` (number of concave portions of the contour)
i. `symmetry`
j. `fractal dimension` ("coastline approximation" - 1)

## Getting Started!
To get started with this project, you can clone this repository and use the breast_cancer_classification.ipynb Jupyter Notebook to run the code. This notebook contains all the necessary code for data preparation, model training, and evaluation.

## Dependencies
This project requires the following Python libraries to be installed:

- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

## Results
The best model achieved an accuracy of 99.7% on the test data using Random Forest Classifier model. Moreover, other types of classifiers were also tested as:         LogisticRegression(),
            DecisionTreeClassifier(),
            RandomForestClassifier(),
            SVC(),
            KNeighborsClassifier(),
            GaussianNB()
            
The confusion matrix and classification report are also available in the notebook.

## License
This project is licensed under the CC BY-NC-SA 4.0 license.

## Citations
This dataset is also available through the UW CS ftp server:
ftp ftp.cs.wisc.edu
cd math-prog/cpo-dataset/machine-learn/WDBC/

Also can be found on `UCI Machine Learning Repository:` https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Diagnostic%29
