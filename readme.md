# Rock VS Mine prediction using Sonar data with a Logistic Regression

This project uses a Logistic Regression model to classify objects as either a rock or a mine based on sonar return data. This is a classic binary classification problem in machine learning.

---
## 📖 Overview

The goal of this project is to build a machine learning model that can accurately determine whether an object detected by sonar is a metal mine or a rock. This has important applications in fields like naval defense and geological surveying. We use the "Sonar, Mines vs. Rocks" dataset and implement a Logistic Regression algorithm from the Scikit-learn library to make the predictions.

---
## 📊 Dataset

The project utilizes the **Sonar, Mines vs. Rocks** dataset, which is publicly available from the UCI Machine Learning Repository.

* **Source**: [UCI Machine Learning Repository: Connectionist Bench (Sonar, Mines vs. Rocks)](https://archive.ics.uci.edu/ml/datasets/Connectionist+Bench+(Sonar,+Mines+vs.+Rocks))
* **Description**: The dataset contains the patterns of sonar signals bounced off a metal cylinder (representing a mine) and a rock at various angles.
* **Features**: It consists of 208 instances and 60 input features, which represent the energy in a particular frequency band.
* **Target**: The target variable has two classes: 'R' for Rock and 'M' for Mine.

---
## 🛠️ Technologies Used

* **Python**: The core programming language.
* **NumPy**: For efficient numerical operations.
* **Pandas**: For data manipulation and loading the dataset from a CSV file.
* **Scikit-learn**: For building and evaluating the Logistic Regression model (`LogisticRegression`, `train_test_split`, `accuracy_score`).
* **Jupyter Notebook**: For interactive development and documentation of the workflow.

---
## 🚀 Setup and Installation

To run this project on your local machine, follow these steps:

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/your-username/your-repository-name.git](https://github.com/your-username/your-repository-name.git)
    cd your-repository-name
    ```

2.  **Create a virtual environment (recommended):**
    ```bash
    # For macOS/Linux
    python3 -m venv venv
    source venv/bin/activate

    # For Windows
    python -m venv venv
    .\venv\Scripts\activate
    ```

3.  **Install the required dependencies:**
    ```bash
    pip install -r requirements.txt
    ```
    *(If you don't have a `requirements.txt` file, you can install the packages manually: `pip install numpy pandas scikit-learn jupyter`)*

---
## ⚙️ How to Run

1.  **Launch Jupyter Notebook:**
    ```bash
    jupyter notebook
    ```
2.  **Open the notebook file:**
    Navigate to and open the `RockVSMinePrediction.ipynb` file (or whatever you have named it).

3.  **Run the cells:**
    Execute the cells in the notebook sequentially to see the data preprocessing, model training, and evaluation steps.

---
## 📈 Model Performance

The Logistic Regression model was trained on 90% of the data and evaluated on the remaining 10% (the test set).

* **Model**: Logistic Regression
* **Evaluation Metric**: Accuracy
* **Result**: The model achieves an accuracy of approximately **85.7%** on the test data.