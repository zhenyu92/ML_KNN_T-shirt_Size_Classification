# A study on Customer T-shirt Size Prediction using K-nearest Neighbor (KNN).
This project is a part of the learning milestone of a Udemy course delivered by [SuperDataScience Team](https://www.udemy.com/machine-learning-classification/). 

### Author
[Derrick Chan](https://github.com/zhenyu92)

[Derrick's Linkedin](https://www.linkedin.com/in/zychan/)

### Project Status: [Completed]

### Project Objective
You own an online clothing business and you would like to develop a new app (or in-store) feature in which customers would enter their own height and weight and the system would predict what T-shirt size should they wear. 
Features are height and weight and output is either L (Large) or S (Small).

`Predictors:`
```
Height (in cms)	
Weight (in kgs)
```

`Target:`
```
T Shirt Size (1: Small, 0: Large)
```

### Environment Prerequisites
`Jupyter Notebook` for Python scripting.

### Instructions
1. Downloaded the [dataset](https://github.com/zhenyu92/ML_KNN_T-shirt_Size_Classification/blob/master/Tshirt_Sizing_Dataset.csv).
2. Run and execute the [IPython](https://github.com/zhenyu92/ML_KNN_T-shirt_Size_Classification/blob/master/KNN%20-%20%20T-shirt%20Size%20Classification.ipynb).
    The following will be covered, and return a prediction.
    ```
    1 Importing Relevant Libraries
    2 Loading Raw Data
    3 Preprocessing
    4 Train Test Split
    5 Select and Train a Model
      5.1 K-nearest Neighbors Model
    6 Apply Model on Test Set
      6.1 Visualize Training Set Results
      6.2 Visualize Test Set Results
    ```   
    
### Model Performance
The model has an average `Precision` & `Recall` of 87%.
![alt text](https://github.com/zhenyu92/ML_KNN_T-shirt_Size_Classification/blob/master/Confusion%20Matrix.JPG "Confusion Matrix")
