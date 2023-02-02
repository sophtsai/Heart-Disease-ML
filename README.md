<div align="center">
<h1 align="center">Predicting Heart Disease</h2>
</div>
<p align="center">
<a href="https://colab.research.google.com/drive/1u_iQfk3NwO_f5LRUTPkHwIKmtBZG4S3c?usp=sharing">Google Colab</a> | 
<a href="https://devpost.com/software/predicting-heart-disease-with-machine-learning">Devpost</a>
</p>

## Project Info 
Heart disease is a type of disease that affects the heart or blood vessels and refers to several types of heart conditions, the most common type in the United States being coronary artery disease (CAD). According to the <a href="https://www.cdc.gov/heartdisease/facts.htm">CDC</a>, heart disease is the leading cause of death for men, women, and people of most racial and ethnic groups in the United States. With almost half of all Americans (<a href=https://www.cdc.gov/heartdisease/risk_factors.htm>47%</a>) having at least 1 in 3 key risk factors for heart disease, it is important for people to be aware of their susceptibility to having a heart disease.

Due to our interest in data analysis and machine learning as well as a common desire to build something that can be beneficial to others, we decided that heart disease is an issue that is important and its prediction and detection is worth exploring. We conducted exploratory data analysis and data preprocessing, utilizing three resampling methods (Random Oversampling, SMOTE, and Random Undersampling) before running 13 different classification models on each resampling method to compare its performance on predicting heart disease.

## Data
The data is originally from a <a href="https://www.cdc.gov/brfss/annual_data/annual_2020.html">2020 CDC telephone survey</a> on the health status of U.S. residents. However, we accessed and utilized an organized and cleaned version of the dataset via <a href="https://www.kaggle.com/datasets/kamilpytlak/personal-key-indicators-of-heart-disease">Kaggle</a>. The Kaggle dataset contains preselected variables having direct or indirect effects on heart disease with values of categorical values convereted to text type and missing records removed.

## Technology
This project was built with Python using Google Colaboratory and various libraries such as MatplotLib, Pandas, Numpy, and Scikit-Learn.

