# Heart Disease Prediction Model

## Objective
The objective of this project is to build a neural network model using PyTorch to predict heart disease based on various health indicators. The project involves preprocessing the dataset, training the model, and evaluating its performance using metrics like accuracy, confusion matrix, classification report, and ROC-AUC curves.

## Dataset Description
The dataset used for this project is named **`heart_disease_health_indicators.csv`**. It contains health-related indicators that are associated with heart disease. The dataset includes the following columns:

- **HighBP**: Indicator for high blood pressure.
- **BMI**: Body Mass Index.
- **Smoker**: Whether the person is a smoker.
- **Diabetes**: Whether the person has diabetes.
- **...and other health indicators...**

The target variable is `HeartDiseaseorAttack`, where:
- `0` indicates no heart disease or attack.
- `1` indicates heart disease or an attack.

## Steps to Run the Code in Jupyter

1. **Clone the repository (if using GitHub):**
   ```bash
   git clone <repository-url>
   cd <repository-directory>
