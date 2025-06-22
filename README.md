🫀 Heart Disease Prediction
A machine learning project that predicts the likelihood of heart disease based on medical attributes. This project aims to assist healthcare professionals and researchers in identifying high-risk patients early using data-driven methods.

📊 Dataset
Source: UCI Heart Disease Dataset

Instances: 303

Features: 13 clinical features + 1 target

🛠️ Technologies Used
Python

Pandas, NumPy

Scikit-learn

Matplotlib, Seaborn

Flask / Streamlit (for UI - optional)

🧬 Features
| Feature Name | Description                                                       |
| ------------ | ----------------------------------------------------------------- |
| age          | Age in years                                                      |
| sex          | Gender (1 = male; 0 = female)                                     |
| cp           | Chest pain type (4 values)                                        |
| trestbps     | Resting blood pressure                                            |
| chol         | Serum cholesterol in mg/dl                                        |
| fbs          | Fasting blood sugar > 120 mg/dl (1 = true)                        |
| restecg      | Resting electrocardiographic results                              |
| thalach      | Maximum heart rate achieved                                       |
| exang        | Exercise induced angina                                           |
| oldpeak      | ST depression induced by exercise                                 |
| slope        | Slope of the peak exercise ST segment                             |
| ca           | Number of major vessels colored by fluoroscopy                    |
| thal         | Thalassemia (3 = normal; 6 = fixed defect; 7 = reversible defect) |
| target       | Heart disease presence (1 = disease; 0 = no disease)              |

📈 Model Performance
| Model               | Accuracy |
| ------------------- | -------- |
| Logistic Regression | 85%      |
| Random Forest       | 88%      |
| SVM                 | 84%      |
| KNN                 | 83%      |






