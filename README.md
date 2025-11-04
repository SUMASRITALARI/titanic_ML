


### 1️ Data Loading & Cleaning
- Loaded data using Pandas  
- Handled missing values (Age, Cabin, Embarked)  
- Encoded categorical features (Sex, Embarked)  

### 2️ Exploratory Data Analysis (EDA)
- Visualized survival rate by **gender**, **class**, **age group**  
- Examined correlations between features and target variable  

### 3️ Feature Engineering
- Created new features:
  - `FamilySize` = SibSp + Parch + 1  
  - `IsAlone` based on FamilySize  
  - Extracted `Title` from passenger names  

### 4️ Model Building
- Trained models like:
  - Logistic Regression  
  - Random Forest  
  - Decision Tree  
  - K-Nearest Neighbors  
- Evaluated accuracy and cross-validation scores  

### 5️ Prediction & Output
- Selected best model based on accuracy and F1 score  
- Generated predictions on the test dataset  

---

## 📊 Results
The model achieved an accuracy of 77% on the validation set.  
Random Forest performed best among all models tested.

---
