# 🧠 Java-based CNN from Scratch

A low-level Java implementation of a Convolutional Neural Network for MNIST digit classification. Features custom matrix ops, manual forward/backpropagation, and modular layer architecture—no external ML libraries used.

# yes NO EXTERNAL LIBRARIES



## 🚀 Features

- Implements **Convolutional Neural Network (CNN)** in pure Java
- Forward and backward **propagation logic from scratch**
- Supports multiple **dense and convolutional layers**
- Handles **matrix operations** without external libraries
- Works with **raw MNIST dataset**
- Tracks **epoch-wise training accuracy**

---

## 🛠️ Setup Instructions

### ✅ Requirements:

- Java 8 (or above)
- Linux or Windows with terminal access

### 🧪 Steps to Run:

1. **Clone the repository**  
   ```bash
   git clone https://github.com/Ultimecia1463/Java-cnn.git
   cd Java-cnn
   ```

2. **Download MNIST files**  

    [mnist_data](https://pjreddie.com/projects/mnist-in-csv/)

   Place the files into the `data/` folder:  
   - mnist_test.csv 
   - mnist_train.csv  

3. **Compile and run**  
   ```bash
   javac Main.java
   java Main
   ```

---

## 📸 Screenshots (Optional)
> Add terminal output or accuracy plots if available.

---

## 📚 References

- [MNIST Database](http://yann.lecun.com/exdb/mnist/)
- Matrix math: personal implementation
- 3Blue1Brown - *Neural Networks* -  https://youtube.com/playlist?list=PLZHQObOWTQDNU6R1_67000Dx_ZCJB-3pi

- Giuseppe Pio Cannata - *“Backpropagation in Fully Convolutional Networks (FCNs)”* - https://towardsdatascience.com/backpropagation-in-fully-convolutional-networks-fcns-1a13b75fb56a

- Sumit Sahu - *“A Comprehensive Guide to Convolutional Neural Networks — the ELI5 way”* - https://towardsdatascience.com/a-comprehensive-guide-to-convolutional-neural-networks-the-eli5-way-3bd2b1164a53

- Pavithra Solai - *“Convolutions and Backpropagations”* - https://pavisj.medium.com/convolutions-and-backpropagations-46026a8f5d2c

- Paul-Louis Pröve - *“An Introduction to different Types of Convolutions in Deep Learning”* - https://towardsdatascience.com/types-of-convolutions-in-deep-learning-717013397f4d