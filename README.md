# SVM-for-classification---Cifar10-compared-to-MNIST
Image Classification with MNIST and CIFAR-10

Contains the implementation and comparative analysis of two datasets: MNIST and CIFAR-10. The project focuses on data preprocessing, neural network architecture, and performance evaluation for both handwritten digit recognition and general object classification.
1. MNIST Dataset (Handwritten Digits)

The MNIST dataset is a collection of 70,000 grayscale images of handwritten digits from 0 to 9.

    Dataset Split: 60,000 training images and 10,000 testing images.

    Image Format: 28x28 pixels, grayscale (1 channel).

    Preprocessing:

        Reshaping: Images are flattened into a 1D vector of 784 pixels for compatibility with standard neural network layers.

        Normalization: Pixel values are scaled from the [0, 255] range to [0, 1] to ensure stable gradient descent.

        One-Hot Encoding: Categorical labels are converted into binary vectors representing the 10 classes.

2. CIFAR-10 Dataset (Object Recognition)

The CIFAR-10 dataset consists of 60,000 color images in 10 different classes (e.g., airplanes, cars, birds, cats, etc.).

    Dataset Split: 50,000 training images and 10,000 testing images.

    Image Format: 32x32 pixels, RGB color (3 channels).

    Preprocessing:

        Normalization: Similar to MNIST, pixel values are normalized to the [0, 1] range.

        Label Encoding: One-hot encoding is applied to the 10 target categories.

--LIBRARIES USED: Keras/TensorFlow, Matplotlib, NumPy



        
