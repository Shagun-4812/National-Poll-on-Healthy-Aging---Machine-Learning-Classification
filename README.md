# National Poll on Healthy Aging - Machine Learning Classification  

**Author**: Shagun Shukla  
**Email ID**: shagun.s-26@scds.saiuniversity.edu.in  
**Date Created**: 05/12/2023  

**Description**: This project utilizes machine learning to predict the **number of doctors a senior visits annually** based on survey responses from the **National Poll on Healthy Aging (NPHA) dataset**. The dataset consists of **714 samples** with **14 input features**, including **age, employment status, physical health, mental health, and sleep issues**. Various **classification models** are trained and evaluated.  

**Problem**: Classification  
**Data**: National Poll on Healthy Aging (NPHA) Dataset  
**Models Used**: Softmax Regression, Support Vector Machines (SVM), Decision Trees, Random Forest, AdaBoost, Gradient Boosting  
**Key Libraries Used**: Scikit-Learn, NumPy, Pandas, Matplotlib  

### **Methods Applied**  
- **Exploratory Data Analysis (EDA)**: Data cleaning, correlation analysis, feature selection  
- **Dimensionality Reduction**: Principal Component Analysis (PCA) to reduce features  
- **Baseline Model**: Softmax Regression  
- **Machine Learning Models**: SVM (Linear, Polynomial, RBF Kernels), Decision Trees, Random Forest, AdaBoost, Gradient Boosting  
- **Hyperparameter Tuning**: Grid Search and Randomized Search  
- **Performance Metrics**: Classification Accuracy, F1-Score, Confusion Matrix  

**Results**:  
- **Random Forest achieved the best performance** with an **F1-score of 0.52** after hyperparameter tuning and feature selection.  

**Note**: For testing and demo, see or run `ML_CourseProject_Notebooks/` containing the implementation notebooks.  
