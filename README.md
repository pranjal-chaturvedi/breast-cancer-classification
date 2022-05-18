# Breast Cancer Classification
### Business Problem
In this case study, the goal is to classify the tumours into malignant (cancerous) or benign (non-cancerous) using the features extracted from the digitised image of a fine needle aspirate (FNA) of a breast mass (for more details, see 'About the dataset' section below).

### The Approach
In this particular problem, various classification machine learning models can be used. When chosing the specific model, there are various factors to take into consideration like the criticality of the problem, architectural choice etc. In this instance, Support Vector Machine (Classification) algorithm is used. There are various advantages and disadvantages for using SVM (which is detailed in this StackExchange post:  https://stats.stackexchange.com/questions/24437/advantages-and-disadvantages-of-svm). It can also help when visualising the data to get a better understanding.

### About the dataset:
The dataset is sourced from University of California Irwine (UCIrwine). Features are computed from a digitised image of a fine needle aspirate (FNA) of a breast mass. They describe characteristics of the cell nuclei present in the image.

The following are the features available:
* Radius (mean of distances from center to points on the perimeter)
* Texture (standard deviation of gray-scale values)
* Perimeter
* Area
* Smoothness (local variation in radius lengths)
* Compactness (perimeter^2 / area - 1.0)
* Concavity (severity of concave portions of the contour)
* Concave points (number of concave portions of the contour)
* Symmetry
* Fractal dimension ("coastline approximation" - 1)

No. of instances: 569.
Class Distribution: 212 Malgnant, 357 Benign.

Target class:
* Malignant
* Benign

This dataset is available directly from Python's Scikit-Learn library.

Dataset source: https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic)
