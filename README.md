Hi, I'm **Chetan Shinagari**  
This repository tracks my daily progress as I learn **Machine Learning** step-by-step.
## 📅 Progress
## Day 1
  **Numpy**
  **Topics Covered:**
- Introduction to NumPy  
- Creating and manipulating arrays  
- Array indexing and slicing  
- Mathematical and statistical operations  
- Broadcasting and reshaping arrays  
- Difference between Python lists and NumPy arrays  

**Key Learnings:**
- NumPy arrays are much faster and more memory-efficient than Python lists.  
- Learned how to perform element-wise operations and basic statistics easily.  

  **Pandas**
  **Topics Covered:**
- Introduction to Pandas  
- DataFrames and Series  
- Importing datasets (CSV, Excel)  
- Handling missing data  
- Data selection using `loc[]` and `iloc[]`  
- Filtering and sorting data  
- Basic statistics using `.describe()`, `.info()`, `.value_counts()`  

**Key Learnings:**
- Pandas helps in data cleaning and manipulation.  
- Realized how easy it is to handle missing values and explore data.  

## Day 2 – Seaborn

* Today I learned Seaborn, a powerful Python library used for data visualization.
   It helps create beautiful and informative statistical graphs easily.

- Topics Covered:
  - Introduction to Seaborn
  - Line plot, Scatter plot, and Relational plots
  - Categorical plots (bar, box, violin)
  - Distribution plots (histplot, distplot)
  - Using hue, style, and palette for customization
  - Adding titles, labels, and improving visualization style

 ##  Day 3 – Machine Learning Basics

##  Topics Covered
Today, I learned about the **basics of Machine Learning** and its **types**.

###  What is Machine Learning?
Machine Learning (ML) is a subset of Artificial Intelligence (AI) that enables systems to automatically learn and improve from experience **without being explicitly programmed**.

###  Key Concepts Learned
- Definition and importance of Machine Learning  
- Real-world examples of ML applications  
- Difference between AI, ML, and Deep Learning  
- Steps involved in a Machine Learning project  

###  Types of Machine Learning
1. **Supervised Learning** – Model learns from labeled data.  
   Examples: Linear Regression, Decision Trees, Random Forest  
2. **Unsupervised Learning** – Model works with unlabeled data to find patterns.  
  Examples: K-Means Clustering, PCA  
3. **Reinforcement Learning** – Model learns by interacting with an environment and receiving rewards or penalties.  
   Examples: Self-driving cars, Game-playing agents  

---

##  Summary
I now understand what ML is, why it’s used, and the main categories it falls into.  
This knowledge forms the **foundation for building and training ML models** in the upcoming days.



## Day 4 – Linear Regression
1. What is Linear Regression?

  - A supervised ML algorithm used for predicting continuous values.
  - Finds the best-fit line between input (X) and output (y).

 2. Types of Linear Regression
  - Simple Linear Regression (one feature)
  - Multiple Linear Regression (multiple features)

 3. Key Concepts
  - Dependent & Independent variables
  - Best-fit line
  - Slope (m) & Intercept (b)
  - Hypothesis function:
   - y=mX+b

 4. Cost Function
  - Measures error between predicted and actual values.
  - Mean Squared Error (MSE) is commonly used.

 5. Gradient Descent
  - Optimization algorithm used to minimize cost.
  - Updates parameters (m, b) until best line is found.

 6. Evaluation Metrics
  - R² Score
  - MAE
  - MSE
  - RMSE

  7. Assumptions of Linear Regression
    - Linearity
    - No multicollinearityHomoscedasticity
    - Normality of residuals
    - Independence of errors

 8. Practical Work Done
    - Loaded dataset (Advertising dataset)
    - Explored features
    - Trained a Linear Regression model
    - Evaluated predictions using R², MSE, RMSE


## Day 5 – Logistic Regression (Simple Summary)
✔ 1. What is Logistic Regression?

  A machine learning algorithm used for classification (yes/no, 0/1).

 2. Sigmoid Function
  Converts output into a probability between 0 and 1.
  If probability > 0.5 → class 1
  Else → class 0

 3. Where Logistic Regression is used
  Spam vs Not Spam
  Diabetic vs Not Diabetic
  Fraud vs Legit
  Pass vs Fail

 4. Types
  Binary (0 or 1)
  Multiclass (more than 2 classes)

 5. Evaluation Metrics
  Accuracy
  Confusion Matrix
  Precision
  Recall
  F1-score

 6. Advantage
  Simple
  Fast
  Good for linearly separable data

 7. Limitation
 Not good for non-linear problems