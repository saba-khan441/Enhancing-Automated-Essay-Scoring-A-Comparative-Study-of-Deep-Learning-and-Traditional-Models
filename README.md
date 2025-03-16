## Enhancing-Automated-Essay-Scoring-A-Comparative-Study-of-Deep-Learning-and-Traditional-Models

**Overview** - Automated Essay Scoring (AES) is one of the technologies that is changing how evaluation in human learning is carried out by enhancing the speed and uniformity of
scoring. Manual grading is a meticulous and often equally laborious activity, and grade feedback is slow to come back in less preserved regions on the social map. AES uses 
machine learning techniques to process essay scores automatically. This paper presents a comparative study of several AES models employing the largest publicly accessible
dataset of contemporary educational standards essays. The models used are: Linear Regression (Cohen’s Kappa: 0.6540), XGBoost (0.7100), LGBM (0.7210), LSTM (0.7710), and BERT
(0.7806). The findings showed, that deep learning models, especially LSTM and BERT, eclipsed the rest, with higher score Estimation precision and reproducibility over the
traditional methods. This study proposes a new public AES system with the goal of improving the efficiency of providing automated evaluation services to teachers while speeding up the objective informational-dependent learning feedback for the students.
### Dataset  
The dataset used in this project is available on **Kaggle**.
download from here https://www.kaggle.com/competitions/learning-agency-lab-automated-essay-scoring-2/data
### OR
download from this repository
![image](https://github.com/user-attachments/assets/6f296225-a68d-42a6-ac2c-81f9f96d2c80)
### Libraries
# General
numpy==1.26.4
pandas==2.2.2
matplotlib==3.7.5
seaborn==0.12.2
scikit-learn==1.2.2
scipy==1.11.4

# Machine Learning Models
xgboost==2.0.3
lightgbm==4.2.0
tensorflow==2.15.0
torch==2.2.0
transformers==4.40.0  # For BERT
sentencepiece==0.2.0   # Required for some BERT models
nltk==3.8.1  # For text preprocessing

# Others
tqdm==4.66.2
joblib==1.4.2
h5py==3.10.0  # For saving deep learning models

###  Models Implemented:
- **Linear Regression** (Cohen’s Kappa: 0.6540)
- **XGBoost** (Cohen’s Kappa: 0.7100)
- **LightGBM** (Cohen’s Kappa: 0.7210)
- **LSTM** (Cohen’s Kappa: 0.7710)
- **BERT** (Cohen’s Kappa: 0.7806)
  
