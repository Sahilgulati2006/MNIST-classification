# MNIST Digit Classification

This repository contains a Python implementation of a neural network for handwritten digit classification using the MNIST dataset. The model is built using TensorFlow and Keras, and it demonstrates end-to-end steps from data preprocessing to building and deploying a predictive system.

---

## **Features**
- Loads and preprocesses the MNIST dataset.
- Visualizes sample images and labels.
- Defines and trains a neural network for classification.
- Evaluates model performance using accuracy and a confusion matrix.
- Builds a predictive system for user-provided images.

---

## **Dataset**
The MNIST dataset consists of 70,000 grayscale images of handwritten digits (28x28 pixels) and their corresponding labels (0-9):
- **Training Data**: 60,000 images.
- **Test Data**: 10,000 images.

---

## **Usage**

### **1. Run the Code**
To execute the script:
```bash
python mnist_digit_classification.py
```

### **2. Predict a Handwritten Digit**
To classify your own handwritten digit:
1. Save your image as a `.png` file (28x28 pixels, grayscale).
2. Provide the image path when prompted by the script.
3. The system will predict and display the digit.

---

## **Model Architecture**
The model consists of:
- **Input Layer**: Flattens the 28x28 input images into a 1D array.
- **Hidden Layers**:
  - 1st Layer: 150 neurons with ReLU activation.
  - 2nd Layer: 50 neurons with ReLU activation.
- **Output Layer**: 10 neurons (one for each digit) with a sigmoid activation function.

---

## **Evaluation**
- **Accuracy**: Achieved an accuracy of ~98% on the test set.
- **Confusion Matrix**: Visualized to analyze prediction performance for each digit.

---

## **Visualization**
### **Training History**
- Training and validation accuracy/loss are plotted for better understanding of model performance.

### **Confusion Matrix Heatmap**
- Displays the true vs. predicted labels for deeper insights.

---

## **Future Enhancements**
- Integrate CNNs for improved accuracy.
- Add support for colored images.
- Deploy the model as a web application.

---

## **Contributing**
Contributions are welcome! If you'd like to enhance the project, feel free to:
1. Fork the repository.
2. Create a new branch for your feature.
3. Submit a pull request.

---

## **Acknowledgements**
- [TensorFlow and Keras Documentation](https://www.tensorflow.org/)
- [MNIST Dataset](http://yann.lecun.com/exdb/mnist/)

---

## **Contact**
For questions or suggestions, please reach out to:- sahilgulati241@gmail.com.

