# Drug Recommendation System

This project is a machine learning-based drug recommendation system that predicts suitable drugs for patients based on their health conditions and attributes such as age, sex, blood pressure, and cholesterol levels.
The Drug Recommendation System acts as a clinical decision support tool by helping doctors or healthcare providers make faster and more informed decisions about which drug to prescribe to a patient based on their medical profile.

# For example:

A patient comes in with high blood pressure, high cholesterol, and a sodium-to-potassium ratio of 15.

Instead of manually analyzing each patient's data, the doctor inputs these values into the system.

The system instantly suggests DrugX as the most suitable option — based on historical data and trained machine learning models.

This saves time, reduces human error, and supports doctors — especially in high-volume hospitals or remote clinics with fewer specialists.



# Features
Predicts drug type using patient input

Built with machine learning (classification models)

Trained on a real-world dataset

User-friendly interface (optional: with Flask/Streamlit)

Customizable and extendable

# Technologies Used
Python

Pandas, NumPy

Scikit-learn (ML Models)

Matplotlib / Seaborn (Visualization)

Flask / Streamlit (optional frontend)

# Dataset
Dataset used: Drug Classification Dataset
Source: UCI Machine Learning Repository

# Feature	Description
Age	               Patient age group
Sex	               Male or Female
BP	               Blood Pressure (Low, Normal, High)
Cholesterol	       (Normal, High)
Na_to_K	           Sodium to Potassium ratio
Drug	             Drug recommended (DrugA–DrugY)
