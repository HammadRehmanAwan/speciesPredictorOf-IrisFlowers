# Iris Species Predictor

This repository contains a simple machine learning workflow for predicting the species of Iris flowers from sepal and petal measurements.

## Project structure

- `speciespredictorof_irisflowers.ipynb` – Jupyter notebook that loads the dataset, trains a classifier, evaluates its performance, and runs a sample prediction.
- `iris-3.csv` – Iris dataset used by the notebook. The columns are:
  - `sepal_length`
  - `sepal_width`
  - `petal_length`
  - `petal_width`
  - `species`

## Getting started

1. Create a Python virtual environment (optional but recommended).
2. Install dependencies:

   ```bash
   pip install pandas scikit-learn
   ```

3. Launch Jupyter Lab or Notebook:

   ```bash
   jupyter notebook speciespredictorof_irisflowers.ipynb
   ```

4. Run all cells to train the model and view predictions.

## Sample prediction

At the end of the notebook you'll find an example that predicts the species for a new measurement. Adjust the values in that cell to classify your own measurements.
