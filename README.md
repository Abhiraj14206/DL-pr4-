# CNN from Scratch: CIFAR-10 Image Classifier

A Deep Learning project that uses Convolutional Neural Networks (CNNs) to classify images from the CIFAR-10 dataset using TensorFlow and Keras. The project explores convolution, padding, strides, pooling, CNN architectures, data augmentation, transfer learning with MobileNetV2, and residual connections.

## 🎯 Project Objectives

- Explore and visualize the CIFAR-10 dataset.
- Understand convolution, padding, strides, and feature maps.
- Implement max pooling and average pooling.
- Build a LeNet-5-style CNN and a custom CNN.
- Train and evaluate image classification models.
- Improve generalization using data augmentation.
- Apply transfer learning and fine-tuning with MobileNetV2.
- Demonstrate residual connections in deep learning.

## 📊 Dataset

**CIFAR-10** contains 60,000 colour images belonging to 10 classes.

- Training images: 50,000
- Test images: 10,000
- Image dimensions: 32 × 32 pixels
- Channels: 3 (RGB)

**Classes:** Airplane, Automobile, Bird, Cat, Deer, Dog, Frog, Horse, Ship, and Truck.

The notebook loads the dataset directly using `tensorflow.keras.datasets.cifar10`.

## 🛠️ Technologies Used

- Python
- TensorFlow and Keras
- NumPy
- Matplotlib
- Pandas
- Scikit-learn
- SciPy
- Jupyter Notebook

## 📁 Project Structure

```text
CNN-CIFAR10-Project/
│
├── DL_PR4A.ipynb
├── README.md
├── models/             # Saved models (generated after running)
└── plots/              # Saved visualizations (generated after running)
```

The `models/` and `plots/` folders may be created or populated when the relevant notebook cells run successfully.

## ⚙️ Installation

Install the required Python libraries:

```bash
pip install tensorflow numpy matplotlib pandas scikit-learn scipy
```

Use a Python version supported by your installed TensorFlow version.

## ▶️ How to Run the Project

1. Download `DL_PR4A.ipynb`.
2. Open the project folder in Jupyter Notebook, JupyterLab, or Visual Studio Code.
3. Install the required dependencies.
4. Select the correct Python environment or notebook kernel.
5. Open `DL_PR4A.ipynb`.
6. Select **Restart Kernel and Run All Cells**.
7. Wait for training and evaluation to finish.
8. Review the generated graphs, classification reports, and model evaluation results.

**Note:** Training time depends on your hardware, batch size, and number of epochs.

## 🧠 Project Modules

### 1. CIFAR-10 Exploration and Preprocessing
- Load and inspect the dataset.
- Visualize sample images and class distributions.
- Normalize image pixel values.
- Prepare labels for model training.

### 2. Convolution, Padding, and Strides
- Demonstrate convolution operations.
- Explore padding and stride settings.
- Visualize feature maps.

### 3. Pooling and CNN Architecture
- Implement max pooling and average pooling.
- Build a LeNet-5-style CNN.
- Design a custom CNN architecture.

### 4. Model Training and Evaluation
- Train CNN models.
- Plot training and validation accuracy.
- Plot training and validation loss.
- Evaluate models using a confusion matrix and classification report.

### 5. Data Augmentation
- Apply image augmentation techniques.
- Train an augmented CNN experiment.
- Compare performance with other experiments.

### 6. Transfer Learning and Fine-Tuning
- Load MobileNetV2 with ImageNet pretrained weights.
- Resize CIFAR-10 images for MobileNetV2.
- Train a classification head.
- Fine-tune selected pretrained layers.

### 7. Residual Connections
- Demonstrate a residual block.
- Understand shortcut connections and their role in deep neural networks.

## 📈 Results

Fill in the table with the actual metrics generated after running the notebook.

| Model | Test Accuracy |
|---|---|
| LeNet-5-style CNN | Add measured result |
| Custom CNN | Add measured result |
| CNN with Data Augmentation | Add measured result |
| MobileNetV2 Transfer Learning | Add measured result |
| MobileNetV2 Fine-Tuning | Add measured result |

Do not enter estimated values. Use the results printed by your notebook.

## 🔍 Evaluation Metrics

The project uses:

- Accuracy
- Training and validation loss
- Training and validation accuracy
- Confusion matrix
- Classification report

## 🚀 Future Improvements

- Experiment with different CNN architectures.
- Tune learning rates, batch sizes, and dropout.
- Improve data augmentation strategies.
- Compare additional pretrained models.
- Add precision, recall, and F1-score comparisons.
- Save experiment histories for reproducibility.

## 👨‍💻 Author

**Abhiraj Medhat**

## 📚 Purpose

This project was developed for educational purposes to practice CNN fundamentals, image classification, model evaluation, data augmentation, and transfer learning.
