# Titanic Dataset Data Cleaning

This repository contains a Google Colab-based data cleaning and preprocessing pipeline for the Titanic dataset. The goal is to prepare the dataset for machine learning tasks by handling missing values, encoding categorical variables, normalizing numerical features, and visualizing outliers.

##  Project Structure

* `TITANIC_DATASET10.ipynb` (original notebook, converted to `.py` for upload)
* `Titanic-Dataset.csv` (dataset used — please ensure to include or provide a link)

##  Features of the Code

 Data Collection & Exploration

* Loaded Titanic dataset using `pandas`.
* Displayed dataset shape, first few rows, data types, and missing values summary.

Handling Missing Values

* Filled missing `Age` values with mean.
* Filled missing `Embarked` values with mode.
* Dropped `Cabin` column due to high proportion of missing data.

Encoding Categorical Features

* (Note: Encoding step placeholder — current code does not apply encoding, can be extended using `pd.get_dummies` or `LabelEncoder`.)

Normalization

** Standardized numerical features using `StandardScaler` from `sklearn`.

 **Outlier Detection**

* Visualized outliers in numerical features using boxplots (`seaborn` + `matplotlib`).

##  Dependencies

The project requires the following Python packages:

```bash
pandas
numpy
matplotlib
seaborn
scikit-learn
```

You can install them using:

bash
pip install pandas numpy matplotlib seaborn scikit-learn


##  How to Run

1. Open the notebook in Google Colab or clone this repo and run locally.
2. Ensure the dataset (`Titanic-Dataset.csv`) is in the correct path (`/content/` for Colab or your local path).
3. Run the code cells step-by-step.

 Example Outputs

* Data info and summary statistics
* Boxplots of numerical columns for outlier detection
* Scaled and cleaned dataset ready for ML tasks

 Next Steps (Suggestions)

* Encode categorical variables like `Sex` and `Embarked`.
* Perform feature selection or engineering.
* Train ML models for survival prediction.
 Author

* This project was developed as part of a data cleaning practice task in Google Colab.
