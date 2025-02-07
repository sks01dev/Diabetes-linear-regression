# Linear Regression on Diabetes Dataset

![Linear Regression](https://upload.wikimedia.org/wikipedia/commons/thumb/3/3a/Linear_regression.svg/512px-Linear_regression.svg.png)

## 📌 Overview
Linear Regression is one of the most well-known algorithms in machine learning and statistics. This project demonstrates its implementation using the Diabetes dataset from `sklearn.datasets`.

## 📊 Dataset
The Diabetes dataset consists of multiple features, but for simplicity, this implementation uses only one feature to predict diabetes progression.

## 🔧 Technologies Used
- Python
- NumPy
- Matplotlib
- scikit-learn

## 📂 Project Structure
```
📦 linear-regression-diabetes
├── linear-regression-dibetes.ipynb  # Jupyter Notebook with code
├── README.md                        # Project Documentation
```


## 📝 Implementation
```python
# Import necessary libraries
import numpy as np
import matplotlib.pyplot as plt
from sklearn import linear_model, datasets

# Load the diabetes dataset
diabetes = datasets.load_diabetes()
X = diabetes.data[:, np.newaxis, 2]
```

## 📈 Results
The model fits a linear regression line to predict diabetes progression based on a single feature.

![Linear Regression Fit](https://upload.wikimedia.org/wikipedia/commons/thumb/3/3a/Linear_regression.svg/512px-Linear_regression.svg.png)

## 💡 Future Improvements
- Use multiple features for better prediction.
- Implement polynomial regression for better accuracy.
