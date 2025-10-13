# Cannabis Consumption Regression

This project uses machine learning to predict the level of cannabis consumption, based on psychological traits and demographic data. The goal is to predict an individual's level of consumption using features such as personality scores, impulsivity, sensation seeking, and other demographic information.

## Data Used

The data used in this project comes from the **Drug Consumption (Quantified) dataset** available at the **UCI Machine Learning Repository**. It includes information such as:

- **Demographics:** Age, gender, education, country, and ethnicity.
- **Personality Traits:** Big Five scores (Neuroticism, Extraversion, Openness, Agreeableness, Conscientiousness).
- **Behavioral Measures:** Impulsivity and Sensation Seeking scores.
- **Drug Consumption:** Frequency of use for multiple substances, including alcohol, caffeine, cannabis, cocaine, ecstasy, and more.

## Project Objective

The goal of this project is to predict the level of cannabis consumption based on psychological and demographic features. The model predicts a **numerical score of consumption**, which represents frequency, from “never used” to “used in the last week.”  

The features used include:

- Personality scores: Nscore, Escore, Oscore, AScore, Cscore
- Behavioral scores: Impulsive, SS
- Demographics: Age, Gender, Education, Country, Ethnicity

The model is trained and evaluated using historical survey data from the UCI repository.

## Project Structure

The project is organized as follows:

```
├── data/
├── model/
├── notebooks/
├── requirements.txt
└── README.md
```


## Models Used

Several popular regression models are considered for this project:

- **Linear Regression**
- **Ridge and Lasso Regression**
- **Decision Tree Regressor**
- **Random Forest Regressor**
- **Gradient Boosting Regressor**
- **XGBoost Regressor**
- **LightGBM Regressor**
- **Support Vector Regressor (SVR)**
- **K-Nearest Neighbors Regressor**

## Requirements

This project was developed and tested with the following dependencies:

- Python 3.8 or higher
- Key libraries:
  - `pandas` – for data manipulation
  - `numpy` – for numerical operations
  - `scikit-learn`, `xgboost`, `lightgbm` – for building and evaluating ML models
  - `matplotlib`, `seaborn` – for data visualization
  - `scipy` – for model training visualization
  - `joblib` – for saving models
  - `sqlite3` – for storing processed data

### Installation

To install all necessary dependencies, use the following command:

```bash
pip install -r requirements.txt
```
---

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgements

This project uses the [Drug Consumption (Quantified) dataset from the UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/373/drug+consumption+quantified). Thanks to UCI for making this dataset publicly available for research purposes.
