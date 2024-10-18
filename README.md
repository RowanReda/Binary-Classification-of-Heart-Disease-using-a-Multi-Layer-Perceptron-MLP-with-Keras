# Neural Network for Iris Classification

## Objective

The objective of this project is to build a neural network for multiclass classification on the famous **Iris dataset** using PyTorch. The network will predict the species of Iris flowers based on four features: sepal length, sepal width, petal length, and petal width. The classification results are evaluated using metrics like accuracy, confusion matrix, and ROC-AUC curves.

## Dataset Description

The dataset used is the Iris dataset, which contains 150 instances of Iris flowers, each belonging to one of three species: Setosa, Versicolor, or Virginica. The dataset consists of:
- 4 features:
  - `SepalLengthCm`
  - `SepalWidthCm`
  - `PetalLengthCm`
  - `PetalWidthCm`
- 1 target (class): 
  - `Species` (3 unique classes: Setosa, Versicolor, Virginica)

The CSV file should be placed at the path specified in the code (`C:\Users\Rabab\Downloads\iris.csv`).

## Steps to Run the Code in Colab
1. Open [Google Colab](https://colab.research.google.com/).
2. Click on **File** > **Upload notebook** to upload your `.ipynb` file.
3. Install the required libraries by running !pip install torch torchvision pandas sklearn matplotlib in a new cell.
4. Upload the iris.csv file to Colab.
5. Ensure the `iris.csv` dataset is uploaded to the same directory as your notebook.
6. Execute each cell sequentially to preprocess the dataset, train the model, and evaluate its performance.

## Dependencies
Ensure that Python (preferably version 3.8 or higher) is installed in your environment.
-pip install numpy
-pip install pandas
-pip install torch
-pip install scikit-learn
-pip install matplotlib seaborn

## Steps in the Code
Load the Dataset: The dataset is loaded from a CSV file and the class distribution is displayed.

### Data Preprocessing:

- The feature values are normalized using StandardScaler.
- The class labels are encoded into numerical values.
- Train-Test Split: The dataset is split into training (80%) and test (20%) sets.

### Neural Network Architecture:
The neural network consists of 3 fully connected (dense) layers and an output layer with softmax activation for multiclass classification.
**Neural Network Performance**: 
   The neural network successfully classified the Iris flower species with high accuracy. The architecture, which included three fully connected layers and ReLU activations, proved effective in learning patterns from the dataset.

### Training: 
The model is trained for 100 epochs using Adam optimizer with L2 regularization (weight decay). A mini-batch size of 16 is used during training.

### Evaluation:
The model is evaluated on the test set for accuracy.
Confusion matrix and classification report are generated.
ROC-AUC curves for each class are plotted to visualize the model's performance.

## Conclusion
 the neural network approach provided an accurate and efficient solution for the Iris classification problem, showing promise for similar multiclass classification tasks.
