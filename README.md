# Data-Driven Modeling of Mechanical Properties in Steels

## Project Overview
This project develops a data-driven machine learning framework to predict key mechanical properties of steels, specifically **Yield Strength (YS)** and **Ultimate Tensile Strength (UTS)**, using chemical composition, processing, and microstructural features. The objective is to evaluate the effectiveness of regression models in capturing structure–property relationships and enabling data-assisted materials design.

---

## Objectives
- Predict Yield Strength and Ultimate Tensile Strength of steels  
- Analyze the influence of composition, processing, and microstructural features  
- Compare classical and ensemble regression models  
- Identify the most reliable predictive model based on accuracy and error consistency  

---

## Methodology

### Data Preprocessing
- Data cleaning and handling of missing values  
- Feature scaling and normalization  
- Quantile transformation for non-normal feature distributions  
- Train–test data splitting  

### Exploratory Data Analysis
- Statistical analysis of input features  
- Correlation analysis to identify influential parameters  

### Feature Engineering
- Selection of relevant composition, processing, and microstructural features  
- Removal of redundant or weakly informative variables  

### Model Development
The following regression models were implemented and evaluated:
- Linear Regression  
- Random Forest Regressor  
- XGBoost Regressor  
- LightGBM Regressor  
- CatBoost Regressor  

Hyperparameter tuning and cross-validation were applied to tree-based models.

### Model Evaluation
Models were evaluated using:
- R² Score  
- Root Mean Squared Error (RMSE)  
- Mean Absolute Error (MAE)  

The final model was selected based on predictive accuracy, robustness, and error stability.

---

## Results and Insights
- Ensemble models significantly outperformed linear regression  
- Tree-based models captured nonlinear structure–property relationships  
- Composition and processing parameters showed strong influence on mechanical properties  
- The selected model demonstrated high accuracy and consistent error performance  

---

---

## Applications
- Accelerated materials design and alloy development  
- Data-assisted prediction of mechanical properties  
- Reduction of experimental trial-and-error costs  
- Decision support for metallurgical research  

---

## Technologies Used

### Programming Language
- Python  

### Libraries and Frameworks
- NumPy  
- Pandas  
- Matplotlib  
- Seaborn  
- Scikit-learn  
- XGBoost  
- LightGBM  
- CatBoost  

### Machine Learning Techniques
- Regression modeling  
- Feature engineering  
- Quantile transformation  
- Hyperparameter tuning  
- Cross-validation  
- Model performance evaluation  

---

## Author
**Makkena Nithiish**  
Dual Degree (B.Tech + M.Tech), IIT Kharagpur  
Metallurgical and Materials Engineering | Financial Engineering  

