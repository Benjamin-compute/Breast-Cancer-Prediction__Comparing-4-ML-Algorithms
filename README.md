# Breast-Cancer-Prediction-Comparing the accuracy of 4 different Machine Learning Algorithms

# **About:**

* The goal is project is to find the best model that performs the best in diagnozing breast cancer, determining whether the cancer tumors  are benign (non-cancerous) or malignant (cancerous)
* Although, this is a .csv multivariate dataset, the features were computed from a digitized image of a fine needle aspirate (FNA) of breast mass, using varying techniques in Linear Programming

# **Data:**

* The number of patients/instances is 569 with 30 features (predictors)
* State origin of the data is **Wisconsin, USA**
* Source: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Diagnostic%29)

How were 30 features extracted from one image data?
1. For each nucleus, ten(10) real-valued features were computed:

    ** radius (mean of distanced from center to points on the perimeter)
    
    ** texture (std of grayscale values)
    
    ** perimeter
    
    ** area
    
    ** smoothness (local variation in radius lengths)
    
    ** compactness (perimeter^2 / area - 1.0)
    
    ** concavity ( severity of concave portions of the contour)
    
    ** concave points (number of concave portions of the contour)
    
    ** symmetry
    
    ** fractal dimension ("coastline approximation" - 1)
    
2. (a) Recorded to 4 decimal places, of each ten features above, the _mean_ , _standard error_ , and _'worst'_ or "largest" (-mean of the 3 largest values), for each image.


2. (b) For example, field 3 = mean radius, field 13 = radius SE, field 23 = worst radius


3. For the response variable's class distribution: 357 benign (B), 212 malignant (M)


# **Machine Learning (ML) Models for Comparisons:**

* K Nearest Neigbor (KNN)
* Logistic Regression
* Random Forest
* Support Vector Machines
