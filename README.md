# Fraud Detection Analytics & Predictive Modeling

*A real-world Data Science collaboration between Universidad Carlos III de Madrid (UC3M) students and Bluetab (an IBM Company).*

**Project Team:** Enica King, Andrea López, César Rodríguez, Emma Rodríguez, and Silvia Díez.
**Supervisors & Mentors:** Prof. Fco. Javier Nogales (UC3M), María Angeles Quesada, Juan Francisco Huete, and Cruz Mateo (Bluetab).

## Objective
Develop a comprehensive analysis of financial transaction patterns using advanced Machine Learning (ML) techniques to classify fraud probability with high precision. The ultimate goal is to improve the detection of illicit activities, minimize economic losses, and strengthen trust in financial operations, thereby contributing to the resilience of the banking and insurance sectors.

## Tech Stack & Tools
- **Data Manipulation:** Python, Pandas, NumPy
- **Machine Learning:** Scikit-Learn (Ensemble methods, classification trees)
- **Imbalanced Data Techniques:** SMOTE, Class Weights tuning
- **Visualization & Dashboarding:** Plotly, Dash/Streamlit

## Project Stages & Methodology

### 1. Data Collection and Exploratory Data Analysis (EDA)
- **Data Modeling:** Structuring a massive financial transaction dataset for analytical processing.
- **EDA:** Identifying statistical anomalies, correlation between features, and visualizing outlier distributions that hint at fraudulent behavior.

### 2. Modeling and Simulation
- **Feature Engineering:** Cleaning raw transaction data and creating highly predictive behavioral features.
- **Class Imbalance Management:** Addressing the severe imbalance inherent in fraud datasets using advanced sampling techniques (like SMOTE) to prevent model bias toward the majority class.
- **Classification Models:** Developing, cross-validating, and tuning predictive algorithms to maximize recall for fraudulent transactions without excessively increasing false positives.

### 3. Visualization and Dashboarding
- **Interactive Dashboards:** Building visual panels to track fraud metrics in real-time.
- **Model Evaluation:** Visualizing performance metrics including Precision, Recall, F1-Score, and ROC-AUC curves.

### 4. Strategies and Business Impact
- **Risk Management:** Designing actionable strategies for fraud prevention based on model probability outputs.
- **ROI Estimation:** Calculating the potential financial impact and Return on Investment (ROI) of deploying the model in a real banking environment.

## How to Run

Clone the repository and install all required packages:

```bash
pip install -r requirements.txt
```
