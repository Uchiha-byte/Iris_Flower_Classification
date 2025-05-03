# Iris Flower Classification

This project implements various machine learning algorithms to classify iris flowers into three species (setosa, versicolor, or virginica) based on their sepal and petal measurements.

## Project Overview

The Iris dataset is a classic dataset in machine learning, containing 150 samples of iris flowers, with 50 samples from each of three species:
- Iris setosa
- Iris versicolor
- Iris virginica

For each sample, four features are measured:
- Sepal length (cm)
- Sepal width (cm)
- Petal length (cm)
- Petal width (cm)

## Project Structure

The project contains multiple implementations of classification algorithms:

1. **Main Classification Notebook** (`iris.ipynb`)
   - Comprehensive analysis and implementation of various classification algorithms
   - Data visualization and exploration
   - Model evaluation and comparison

2. **SVM Implementation** (`SVM Iris.ipynb`)
   - Support Vector Machine classification
   - Hyperparameter tuning
   - Performance evaluation

3. **KNN Implementation** (`KNN on Iris Dataset/`)
   - K-Nearest Neighbors classification
   - Detailed analysis and visualization
   - PDF report included

## Dataset

The dataset is stored in `iris_data.csv` and contains:
- 150 samples (50 per species)
- 4 features per sample
- 3 target classes

## Requirements

To run this project, you need:
- Python 3.x
- Jupyter Notebook
- Required Python packages:
  - pandas
  - numpy
  - scikit-learn
  - matplotlib
  - seaborn

## Installation

1. Clone this repository:
```bash
git clone [https://github.com/Uchiha-byte/Iris_Flower_Classification.git]
```

2. Install the required packages:
```bash
pip install pandas numpy scikit-learn jupyter matplotlib seaborn
```

## Usage

1. Start Jupyter Notebook:
```bash
jupyter notebook
```

2. Open any of the notebooks:
   - `iris.ipynb` for the main implementation
   - `SVM Iris.ipynb` for SVM implementation
   - `KNN on Iris Dataset/iris_Flower_Classification_using_KNN.ipynb` for KNN implementation

3. Run the cells in sequence to:
   - Load and explore the data
   - Preprocess the data
   - Train the models
   - Evaluate the results
   - Visualize the findings

## Results

The project demonstrates the effectiveness of different machine learning algorithms in classifying iris flowers. Each implementation includes:
- Data visualization
- Model training
- Performance metrics
- Confusion matrices
- Classification reports

## License

This project is open-source and available under the MIT License.

## Acknowledgments

- The Iris dataset is a classic dataset in machine learning
- Special thanks to the scikit-learn community for their excellent documentation and tools 
