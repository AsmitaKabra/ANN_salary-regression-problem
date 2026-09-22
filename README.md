# ANN Salary Regression

A Deep Learning regression project that uses an **Artificial Neural Network (ANN)** built with **TensorFlow/Keras** to predict employee salary.

## 📌 Project Overview

This project demonstrates how an Artificial Neural Network can be used to solve a **regression problem**.

The project covers the complete Deep Learning workflow:

* Data preprocessing
* Categorical feature encoding
* Feature scaling
* Train-test splitting
* Building an Artificial Neural Network
* Model compilation
* Model training
* Model evaluation
* Saving the trained model
* Saving preprocessing objects for future predictions

---

## 🧠 Model Architecture

The ANN is built using a Sequential model with the following architecture:

```text
Input Layer
      ↓
Dense Layer — 64 Neurons — ReLU
      ↓
Dense Layer — 32 Neurons — ReLU
      ↓
Output Layer — 1 Neuron — Linear
      ↓
Salary Prediction
```

### Model Configuration

| Parameter               | Value                     |
| ----------------------- | ------------------------- |
| Model                   | Sequential ANN            |
| Framework               | TensorFlow / Keras        |
| Hidden Layer 1          | 64 neurons                |
| Hidden Layer 2          | 32 neurons                |
| Hidden Layer Activation | ReLU                      |
| Output Layer            | 1 neuron                  |
| Output Activation       | Linear                    |
| Optimizer               | Adam                      |
| Loss Function           | Mean Absolute Error (MAE) |
| Problem Type            | Regression                |

---

## 🛠️ Technologies Used

* **Python**
* **TensorFlow**
* **Keras**
* **Pandas**
* **NumPy**
* **Scikit-learn**
* **Jupyter Notebook**

---

## 📂 Project Structure

```text
ANN_salary-regression-problem/
│
├── Churn_Modelling.csv
├── salaryregression.ipynb
├── salary_regression_model.h5
├── label_encoder.pkl
├── onehot_encoder.pkl
├── scaler.pkl
└── README.md
```

---

## 🔄 Project Workflow

### 1. Data Loading

The dataset is loaded using **Pandas** and explored to understand the available features and target variable.

### 2. Data Preprocessing

The data is prepared before feeding it into the neural network.

The preprocessing includes:

* Handling categorical variables
* Label Encoding
* One-Hot Encoding
* Feature scaling
* Separating independent and dependent variables

### 3. Train-Test Split

The processed dataset is divided into training and testing datasets.

The training data is used to train the neural network, while the testing data is used to evaluate its performance on unseen data.

### 4. Building the ANN

A Sequential Artificial Neural Network is created using TensorFlow/Keras.

The network consists of:

```text
64 Neurons → ReLU
        ↓
32 Neurons → ReLU
        ↓
1 Neuron → Linear
```

### 5. Compiling the Model

The model is compiled using:

```python
optimizer = "adam"
loss = "mean_absolute_error"
```

The **Adam optimizer** is used to optimize the network weights, while **Mean Absolute Error (MAE)** is used as the loss function for the regression task.

### 6. Training the Model

The ANN is trained on the training dataset so that it can learn the relationship between the input features and salary.

### 7. Model Evaluation

The trained model is evaluated using the test dataset to understand how well it performs on previously unseen data.

### 8. Saving the Model

The trained ANN model is saved so that it can be reused without retraining from scratch.

The preprocessing objects are also saved to ensure that new input data can be transformed in the same way as the training data.

---

## 📦 Saved Files

| File                         | Purpose                         |
| ---------------------------- | ------------------------------- |
| `salary_regression_model.h5` | Trained ANN model               |
| `label_encoder.pkl`          | Saved Label Encoder             |
| `onehot_encoder.pkl`         | Saved One-Hot Encoder           |
| `scaler.pkl`                 | Saved feature scaler            |
| `salaryregression.ipynb`     | Complete project implementation |
| `Churn_Modelling.csv`        | Dataset                         |

---

## ▶️ How to Run the Project

### Step 1: Clone the Repository

```bash
git clone https://github.com/AsmitaKabra/ANN_salary-regression-problem.git
```

### Step 2: Navigate to the Project

```bash
cd ANN_salary-regression-problem
```

### Step 3: Install Required Libraries

```bash
pip install tensorflow pandas numpy scikit-learn jupyter
```

### Step 4: Start Jupyter Notebook

```bash
jupyter notebook
```

### Step 5: Open the Notebook

Open:

```text
salaryregression.ipynb
```

Run the cells sequentially to perform data preprocessing, train the ANN, evaluate the model, and save the trained model.

---

## 🎯 Key Learning Outcomes

Through this project, I practiced:

* Understanding Deep Learning for regression
* Building Artificial Neural Networks
* Working with TensorFlow and Keras
* Designing neural network architectures
* Using activation functions such as ReLU and Linear
* Encoding categorical features
* Feature scaling
* Splitting data into training and testing sets
* Compiling and training neural networks
* Evaluating regression models
* Saving trained Deep Learning models
* Saving preprocessing objects using Pickle

---

## 🚀 Future Improvements

The project can be further improved by:

* Building a **Streamlit web application**
* Deploying the trained model
* Creating an interactive salary prediction interface
* Performing hyperparameter tuning
* Experimenting with different ANN architectures
* Comparing the ANN with traditional regression algorithms
* Adding model performance visualizations
* Improving prediction performance

---

## 📚 Project Highlights

```text
✔ End-to-End Deep Learning Project
✔ Artificial Neural Network
✔ Regression Problem
✔ TensorFlow / Keras
✔ Data Preprocessing
✔ Feature Encoding
✔ Feature Scaling
✔ Model Training
✔ Model Evaluation
✔ Model Saving
```

---

## 👩‍💻 Author

### Asmita Kabra

**B.Tech — Artificial Intelligence & Data Science**

Aspiring Machine Learning Engineer

[GitHub](https://github.com/AsmitaKabra)

---

## ⭐ Support

If you found this project useful or interesting, consider giving the repository a ⭐ **Star**!

---

**Built with Python, TensorFlow & Keras 🧠**
