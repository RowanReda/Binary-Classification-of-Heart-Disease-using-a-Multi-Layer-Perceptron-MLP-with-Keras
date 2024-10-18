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

## Steps to Run the Code in Colab
1. Open [Google Colab](https://colab.research.google.com/).
2. Click on **File** > **Upload notebook** to upload your `.ipynb` file.
3. Install the required libraries by running !pip install torch torchvision pandas sklearn matplotlib in a new cell.
4. Upload the Housing-1.csv file to Colab.
5. Ensure the `Housing-1.csv` dataset is uploaded to the same directory as your notebook.
6. Execute each cell sequentially to preprocess the dataset, train the model, and evaluate its performance.

## Dependencies
Ensure that Python (preferably version 3.8 or higher) is installed in your environment.
-pip install numpy
-pip install pandas
-pip install torch
-pip install scikit-learn
-pip install matplotlib seaborn

## Conclusion
This project builds a neural network model to classify individuals with or without heart disease using PyTorch. The model’s performance is evaluated using accuracy, confusion matrix, classification report, and ROC-AUC curves for multi-class classification.
