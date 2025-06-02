#  CIFAR-10: Comparing MLP and CNN

## Project Overview

This project compares two neural network approaches for image classification on the **CIFAR-10** dataset:
- Multilayer Perceptron (**MLP**)
- Convolutional Neural Network (**CNN**)

The main goal is to demonstrate how using convolutional layers significantly boosts performance compared to a plain fully-connected network.  
The project also includes visualizations of convolutional filters, feature maps (activations), and a confusion matrix for the CNN.

---

##  Dataset: CIFAR-10

- **10 classes:** airplane, automobile, bird, cat, deer, dog, frog, horse, ship, truck
- **50,000** training and **10,000** test images (32x32 pixels, RGB)

**Sample images:**
![Sample images](img/1.png)

**Class distribution:**
![Class distribution](img/2.png)

---

## Model Architectures

**MLP Architecture:**  
![MLP Architecture](img/3.png)

**MLP Training Progress:**  
![MLP Training](img/4.png)

**CNN Architecture:**  
![CNN Architecture](img/5.png)

**CNN Training Progress:**  
![CNN Training](img/6.png)

---

##  Model Evaluation

**CNN Confusion Matrix:**  
![CNN Confusion Matrix](img/7.png)

---

##  CNN Internals

**Visualization of the first convolutional filters:**  
![Conv Filters](img/8.png)

**Visualization of the first layer activations:**  
![Conv Activations](img/9.png)

---

##  MLP vs CNN: Validation Accuracy

![CNN vs MLP Validation Accuracy](img/10.png)

- The CNN clearly outperforms the MLP on validation accuracy.
- Convolutional layers help the model learn spatial features, which is essential for image data.

---

##  How to Run

1. Clone this repository.
2. Install requirements (`pip install -r requirements.txt`).
3. Run the notebook or script to reproduce all results.

---

## 🤔 Key Takeaways

- **MLP** is not well suited for image recognition tasks, as it does not capture spatial dependencies.
- **CNN** significantly improves accuracy by leveraging local patterns in images.
- Visualizing filters and activations helps to understand what the network is learning.

---

## Author

Nikita Marshchonok

---

