
# 🧠 CNN-Based Image Classification - MNIST Subset

This project implements a Convolutional Neural Network (CNN) to classify handwritten digits using a subset of the MNIST dataset. The model is trained and evaluated using varying CNN parameters to explore the impact on accuracy and loss.

## 📌 Project Overview

- Dataset: Subset of MNIST (4 digit classes)
- Architecture: 2 Convolutional Layers + MaxPooling + Fully Connected + Softmax
- Task: Multi-class image classification

## 🚀 Features

- Subset selection from MNIST using a fixed seed
- Custom preprocessing with normalization
- Training and evaluation under varying CNN configurations
- Plotting training/testing accuracy and loss over epochs

## 🗂️ File Descriptions

| File                  | Description                                                  |
|-----------------------|--------------------------------------------------------------|
| `precode.py`          | Preprocesses and subsets the MNIST dataset                  |
| `baseline.ipynb`      | Baseline CNN implementation using Keras                     |
| `project3.ipynb`      | Final model training with required hyperparameters          |
| `project3_submission.ipynb` | Submission notebook with output results and evaluation       |
| `Project Description.pdf` | Official project instructions                            |

## 🛠️ How to Run

### Step 1: Install Dependencies

```bash
pip install numpy keras tensorflow matplotlib
```

### Step 2: Prepare the Dataset

Ensure you have the `mnist` module and internet connection to auto-download the MNIST dataset via Keras or implement your own version of `train_images()` and `train_labels()`.

### Step 3: Run Experiments

- Open `baseline.ipynb` to train the base model
- Open `project3.ipynb` to explore new CNN configurations
- Evaluate performance and adjust kernel size, number of filters, etc.
- Use `project3_submission.ipynb` for submitting final results

## 📊 Evaluation Metrics

- Accuracy (Training & Testing)
- Loss (Training & Testing)
- Plotted over 10 epochs

---

📄 For full instructions, refer to the included `Project Description.pdf`.
