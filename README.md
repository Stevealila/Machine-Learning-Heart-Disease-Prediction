# Machine Learning Heart Disease Prediction

This project uses machine learning techniques to predict heart disease. The dataset includes various features such as age, sex, chest pain type, resting blood pressure, cholesterol levels, and more. Different models are trained and evaluated to determine the best approach for prediction.

## Project Structure

- `exercise.ipynb`: Jupyter notebook containing all data preprocessing, model training, and evaluation steps.

## Getting Started

### Prerequisites

Make sure you have the following installed:

- Python 3.x
- Jupyter Notebook
- Required Python libraries (listed below)

### Installation

1. Clone the repository:

   ```sh
   git clone https://github.com/Stevealila/Machine-Learning-Heart-Disease-Prediction.git
   cd Machine-Learning-Heart-Disease-Prediction
   ```

2. Install the required packages:

   ```sh
   pip install pandas matplotlib seaborn numpy scipy scikit-learn
   ```

### Usage

1. Open the Jupyter notebook:

   ```sh
   jupyter notebook exercise.ipynb
   ```

2. Run the cells in the notebook to preprocess the data, train the models, and evaluate their performance.

### Models Used

- Support Vector Machine (SVM)
- Random Forest
- Bagging Classifier with SVM

### Results

- **Support Vector Classifier**: 87.55% accuracy
- **Random Forest Classifier**: 85.21% accuracy
- **Bagged Support Vector Classifier**: 87.94% accuracy

### License

This project is licensed under the MIT License.

### Acknowledgements

- Dataset used from the Kaggle Data Science platform.
- Exercise created by [Codebasics YouTube channel](https://www.youtube.com/@codebasics)
- Inspired by various machine learning tutorials and guides.
