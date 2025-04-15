# 🐱🐶 Cat and Dog Image Classifier

This project is part of the [Machine Learning with Python](https://www.freecodecamp.org/learn/machine-learning-with-python/) course by **freeCodeCamp**. The goal is to build a **convolutional neural network (CNN)** using **TensorFlow 2.0** and **Keras** that can classify images of cats and dogs with at least **63% accuracy**.

> ✅ Extra credit if you reach **70% accuracy**!

---

## 📌 Project Overview

You’ll build and train a CNN that can distinguish between images of cats and dogs using a structured dataset. You'll also implement image preprocessing, data augmentation, training/validation logic, and final evaluation through predictions.

This project runs in **Google Colaboratory** and involves working directly with Python and TensorFlow code in an interactive notebook environment.

---

## 📁 Dataset Structure

After downloading and unzipping, the dataset has the following structure:

```
cats_and_dogs/
│
├── train/
│   ├── cats/
│   └── dogs/
│
├── validation/
│   ├── cats/
│   └── dogs/
│
└── test/
    ├── 1.jpg
    ├── 2.jpg
    └── ...
```

- **Training** and **validation** sets are labeled and divided into subfolders.
- **Test** set contains unlabeled images used for final predictions.

---

## 🧠 What You'll Do

| Step | Description |
|------|-------------|
| Cell #3 | Set up `ImageDataGenerator` for train, validation, and test data. |
| Cell #4 | Visualize sample training images. |
| Cell #5 | Recreate the training generator with **data augmentation** (4–6 transformations). |
| Cell #6 | Visualize augmented images. |
| Cell #7 | Build the CNN with Conv2D, MaxPooling2D, Flatten, and Dense layers. |
| Cell #8 | Train the model using `model.fit()`. |
| Cell #9 | Plot training/validation accuracy and loss. |
| Cell #10 | Predict on the test images and visualize predictions. |
| Cell #11 | Evaluate your model accuracy (must be ≥ 63% to pass). |

---

## 🛠 Technologies Used

- Python 3
- TensorFlow 2.0
- Keras
- Google Colab
- Matplotlib & NumPy

---

## 🎯 Goal

Build a model that classifies unseen images of cats and dogs with **≥63% accuracy**. If your model performs better, even better!

---

## 📎 Submission

Once your model passes the test:

1. Save a copy of your Google Colab notebook.
2. Share the **Colab link** (make sure link sharing is turned on).
3. Example link:  
   `https://colab.research.google.com/drive/your-notebook-id`

---

## 🔗 Project Link

You can find the original project here:  
👉 [Cat and Dog Image Classifier on freeCodeCamp](https://www.freecodecamp.org/learn/machine-learning-with-python/machine-learning-with-python-projects/cat-and-dog-image-classifier)

---

## 🧑‍💻 Author

Project completed as part of  
**CURSO DE ENTRENAMIENTO DE MODELOS DE FREE CODE CAMP (MACHINE LEARNING)**  
Available at: [freeCodeCamp.org](https://www.freecodecamp.org/learn/machine-learning-with-python/)
Lucía María Doval Abilleira

---
