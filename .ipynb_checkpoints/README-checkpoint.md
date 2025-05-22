# 🌸 Feedforward Neural Network for Iris Classification

This project demonstrates how to build, train, and use a **Feedforward Neural Network (FFNN)** using **Keras** to classify **Iris flower species** based on four flower measurements.

It is divided into two main parts:

- `ModelTrain.html`: Model creation, training, and saving
- `ModelPredict.html`: Model loading and prediction on new data

---

## 📁 Project Files

| File                | Description                                    |
|---------------------|------------------------------------------------|
| `ModelTrain.html`   | Jupyter HTML export for training the model     |
| `ModelPredict.html` | Jupyter HTML export for using the trained model|
| `FFNN.iris.model.keras` | Saved Keras model (generated after training) |
| `README.md`         | Project overview and usage guide               |

---

## Model Architecture

- Input layer: 4 features (sepal length, sepal width, petal length, petal width)
- Hidden layers: 16, 40, and 10 neurons with ReLU activation
- Output layer: 3 neurons with softmax activation (for 3 classes)

## Training

- Loss function: categorical_crossentropy
- Optimizer: Adam
- Metrics: Accuracy
- Epochs: 200
- Batch size: 4
- 80/20 train/test split

## 🧠 Problem Statement

Given a dataset with 4 features:
- Sepal length
- Sepal width
- Petal length
- Petal width

...the goal is to classify the input into one of the following species:
- Iris-setosa
- Iris-versicolor
- Iris-virginica

---

## 🧰 Requirements

Make sure Python 3 is installed. Then install dependencies:

```bash
pip install tensorflow keras numpy matplotlib
