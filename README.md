##Group members list is available in [GROUP_MEMBERS.docx](GROUP_MEMBERS.docx)
##memebers

NAME	                REG NO
BRIAN OCHIENG’	    SC211/0473/2022
MARTIN MWANGI	    SC211/0708/2022
LABAN BIWOTT	    SC211/0497/2022
SILA WAMBUA	       SC211/0535/2022
MOSES CHEGE	       SC211/1937/2022
SIKAMOI PURITY	    SC211/1358/2020
CHRISTOPHER AKUNO	 SC211/0471/2022



## FashionMNIST-ANN
## Fashion MNIST Image Classification Using ANN

## Overview
This project demonstrates the implementation of an **Artificial Neural Network (ANN)** for classifying grayscale images of clothing items from the **Fashion-MNIST dataset**. The notebook follows a complete workflow including:

1. Downloading and loading the dataset
2. Visualizing sample images
3. Data preprocessing (normalization)
4. Building a multi-layer ANN model
5. Training and evaluating the model
6. Visualizing model performance (loss, accuracy, predictions)
7. Additional displays including model architecture diagram and confusion matrix

The model achieves high accuracy (~90%+) on unseen test data, showing that ANNs can effectively classify fashion images.

---

## Dataset
- **Dataset Name:** Fashion-MNIST
- **Number of Training Images:** 60,000
- **Number of Test Images:** 10,000
- **Image Size:** 28 × 28 pixels
- **Number of Classes:** 10 (T-shirt/top, Trouser, Pullover, Dress, Coat, Sandal, Shirt, Sneaker, Bag, Ankle boot)
- **Source:** [Keras Datasets](https://keras.io/api/datasets/fashion_mnist/)

---

## Model Architecture
- **Input Layer:** Flatten 28×28 images to 784 features
- **Hidden Layer 1:** Dense layer with 128 neurons, ReLU activation
- **Hidden Layer 2:** Dense layer with 64 neurons, ReLU activation
- **Output Layer:** Dense layer with 10 neurons, Softmax activation (for 10 classes)

**Optimizer:** Adam  
**Loss Function:** Sparse Categorical Crossentropy  
**Metrics:** Accuracy

---

## Installation & Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/YourUsername/FashionMNIST-ANN.git
   
