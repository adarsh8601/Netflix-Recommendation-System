# 🎬 Netflix Movie Recommendation System using SVD

## Overview
A collaborative filtering-based recommendation engine built using Singular Value Decomposition (SVD) algorithm to predict user movie ratings and provide personalized recommendations.

## 📊 Project Highlights
- Processed and cleaned **500K+ user-movie ratings** from Netflix dataset
- Achieved **RMSE of ~0.9** using SVD matrix factorization
- Implemented **top-N personalized recommendations** for users
- Performed comprehensive **EDA with visualizations** of rating patterns
- Built **end-to-end ML pipeline** with cross-validation and evaluation metrics

## 🛠️ Technologies Used
- **Python** - Core programming language
- **Pandas & NumPy** - Data manipulation and analysis
- **Matplotlib & Seaborn** - Data visualization
- **Scikit-Surprise** - Collaborative filtering and SVD implementation
- **Machine Learning** - SVD algorithm, train-test split, cross-validation

## 📈 Key Features
✅ Data cleaning and preprocessing of Netflix ratings  
✅ Exploratory Data Analysis with distribution plots  
✅ Feature engineering (user/movie statistics)  
✅ SVD model training with hyperparameter tuning  
✅ Model evaluation using RMSE and MAE  
✅ Personalized movie recommendations  

## 🎯 Results
- **RMSE**: ~0.9
- **MAE**: ~0.7
- Successfully generates top-N movie recommendations for any user

## 📂 Project Structure
```
├── data_cleaning.py          # Data preprocessing
├── eda_visualization.py      # Exploratory analysis
├── feature_engineering.py    # Feature creation
├── model_building.py         # Model training, Model evaluation, Recommendation engine
```

## 🚀 How to Run
```bash
pip install pandas numpy matplotlib seaborn scikit-surprise
python svd_model.py
```
