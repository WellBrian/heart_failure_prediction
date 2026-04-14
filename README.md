
# Heart Failure Prediction

## Description

Cardiovascular diseases (CVDs) are the number 1 cause of death globally, taking an estimated 17.9 million lives each year, which accounts for 31% of all deaths worldwide. Heart failure is a common event caused by CVDs. People with cardiovascular disease or who are at high cardiovascular risk (due to the presence of one or more risk factors such as hypertension, diabetes, hyperlipidaemia or already established disease) need early detection and management wherein a machine learning model can be of great help.

The aim is to classify / predict whether a patient is prone to heart failure depending on multiple attributes. It is a binary classification problem with multiple numerical and categorical features.

## Dataset

The dataset contains the following attributes:

- **Age**: age of the patient [years]
- **Sex**: sex of the patient [M: Male, F: Female]
- **ChestPainType**: chest pain type [TA: Typical Angina, ATA: Atypical Angina, NAP: Non-Anginal Pain, ASY: Asymptomatic]
- **RestingBP**: resting blood pressure [mm Hg]
- **Cholesterol**: serum cholesterol [mm/dl]
- **FastingBS**: fasting blood sugar [1: if FastingBS > 120 mg/dl, 0: otherwise]
- **RestingECG**: resting electrocardiogram results [Normal: Normal, ST: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV), LVH: showing probable or definite left ventricular hypertrophy by Estes' criteria]
- **MaxHR**: maximum heart rate achieved [Numeric value between 60 and 202]
- **ExerciseAngina**: exercise-induced angina [Y: Yes, N: No]
- **Oldpeak**: oldpeak = ST [Numeric value measured in depression]
- **ST_Slope**: the slope of the peak exercise ST segment [Up: upsloping, Flat: flat, Down: downsloping]
- **HeartDisease**: output class [1: heart disease, 0: Normal]

## Installation

To run this project, you need to install the following dependencies:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

You can install them using pip:

```
pip install pandas numpy matplotlib seaborn scikit-learn
```

## Usage

1. Clone the repository or download the files.
2. Ensure the `heart.csv` dataset is in the same directory as the notebook.
3. Open the `heart-failure-prediction.ipynb` notebook in Jupyter or VS Code.
4. Run the cells in order to perform EDA and modeling.

## Methodology

The notebook covers:
- Dataset Information
- Exploratory Data Analysis (EDA)
- Summary of EDA
- Modeling with various algorithms: Logistic Regression, SVM, Decision Tree, Random Forest, KNN
- Visualization of results

## Results

| Sr. No. | ML Algorithm | Accuracy | Cross Validation Score | ROC AUC Score |
|---------|--------------|----------|-------------------------|---------------|
| 1 | Logistic Regression | 87.50% | 91.12% | 87.43% |
| 2 | Support Vector Classifier | 87.50% | 90.53% | 87.43% |
| 3 | Decision Tree Classifier | 84.78% | 89.09% | 84.62% |
| 4 | Random Forest Classifier | 84.24% | 92.91% | 84.06% |
| 5 | K-Nearest Neighbors Classifier | 81.52% | 89.34% | 81.36% |

## Requirements

- Python 3.x
- Jupyter Notebook or VS Code with Python extension

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Author

Brian

## Acknowledgments

- Dataset sources and citations
- Libraries and frameworks used
- Inspiration and references
- Medical research papers on heart failure prediction
- Scikit-learn and Pandas documentation
- Contributors and testers
