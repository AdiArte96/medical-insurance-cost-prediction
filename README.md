\# Medical Insurance Cost Prediction Using Machine Learning



🎓 MBA Project | 🏫 University Canada West  

📅 June 2024 | 👨‍🎓 Aditya Arte



This project applies machine learning algorithms in Python to predict medical insurance costs based on demographic and health-related features. The models used include Linear Regression, Decision Tree, K-Nearest Neighbours, and Piecewise Linear Regression.



---



\## 📌 Project Overview



Predicting insurance charges helps both policyholders and providers manage risks and pricing. The dataset used consists of 1,338 records and includes attributes such as age, BMI, number of children, gender, region, and smoking status.



---



\## 🔍 Objective



To compare the performance of multiple machine learning models for predicting medical charges, and determine which model provides the best predictive accuracy.



---



\## 🛠 Tools \& Techniques



\- \*\*Python (Jupyter Notebook)\*\*  

\- \*\*scikit-learn\*\*  

\- \*\*Pandas / Numpy / Matplotlib\*\*  

\- \*\*Dummy Variable Creation\*\*  

\- \*\*Data Normalization\*\*  

\- \*\*Model Evaluation Metrics\*\* (MSE, RMSE, MAE, R²)  

\- \*\*Piecewise Linear Regression\*\*



---



\## 📈 Model Performance Summary



| Model                     | R² Score | RMSE     | MAE     |

|--------------------------|----------|----------|---------|

| Linear Regression        | 70.96%   | 4,841.21 | 3,316.73|

| Decision Tree            | 73.40%   | 5,384.60 | 2,300.56|

| K-Nearest Neighbours     | 63.77%   | 5,290.50 | 3,294.13|

| \*\*Piecewise Regression\*\* | \*\*84.11%\*\* | \*\*4,826.67\*\* | \*\*2,876.09\*\* |



> Piecewise Linear Regression outperformed all other models on both training and test sets.



---



\## 📊 Visualizations



\- Histogram distributions of Age and BMI  

\- Boxplots for outlier detection  

\- Frequency plots for categorical variables  



(Exported from notebook — see `/images/`)



---



\## 📁 Project Structure



```plaintext

├── notebook/

│   └── ML\_Assignment.ipynb               # Python code with model training \& evaluation

├── report/

│   └── MLAssignment\_Report.docx          # Final academic write-up

├── images/

│   └── \*.png                             # Visuals generated in notebook

