#  Handwritten Digit Recognition using SVM

## 📌 Project Overview

This project focuses on recognizing handwritten digits (0–9) using a Machine Learning classification algorithm called **Support Vector Machine (SVM)**.

The model takes an 8×8 image of a handwritten digit and predicts which digit it represents.

## 🎯 Objectives

- Understand how images are represented as numerical pixel values.
- Load and explore handwritten digit data.
- Visualize handwritten digit images using Matplotlib.
- Train a Support Vector Machine classifier.
- Evaluate model accuracy using a test dataset.
- Compare different SVM kernel and parameter settings.

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

## 📂 Project Structure

```text
Handwritten-Digit-Recognition-SVM/
│
├── data/
│   └── digits.csv
│
├── 02_handwritten_digit_recognition_svm.ipynb
├── requirements.txt
├── README.md
└── .gitignore
```

## 📊 Dataset

The dataset contains **1,797 handwritten digit images**.

Each image is represented by 64 pixel values arranged as an 8×8 grid.

- `pixel_0` to `pixel_63`: Pixel brightness values.
- `label`: Actual handwritten digit (0–9).

## 🤖 Machine Learning Algorithm

This project uses **Support Vector Machine (SVM)** for multi-class classification.

Different SVM configurations are compared:

- Linear kernel
- RBF kernel
- RBF kernel with gamma = 0.001
- RBF kernel with gamma = 0.001 and C = 0.1

The model is evaluated using accuracy on the test dataset.

## ⚙️ How to Run the Project

### 1. Clone the repository

```bash
git clone https://github.com/YOUR-GITHUB-USERNAME/Handwritten-Digit-Recognition-SVM.git
```

### 2. Open the project folder

```bash
cd Handwritten-Digit-Recognition-SVM
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Run Jupyter Notebook

```bash
jupyter notebook
```

Open `02_handwritten_digit_recognition_svm.ipynb` and run the cells.

## 📈 What I Learned

- How image data is stored as pixel values.
- How to visualize 8×8 handwritten digit images.
- How to train and test an SVM classification model.
- How to compare different model settings.
- How to evaluate a classification model using accuracy.

## 🚀 Future Improvements

- Display incorrectly predicted digits.
- Experiment with additional SVM parameters.
- Improve model performance.
- Build a simple web application for digit recognition.

## 👨‍💻 Author

**ATHUL R.R**

GitHub: [@athulrr4](https://github.com/athulrr4)

## 📄 License

This project is created for educational and learning purposes.
