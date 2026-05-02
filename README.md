# Machine Learning and Deep Learning Labs

This repository contains a collection of practical lab exercises completed for the **Machine Learning and Deep Learning** course.

The labs focus on building a strong foundation in PyTorch, neural network training, computer vision, transfer learning, and model evaluation.  
They include hands-on implementations of tensor operations, data loading pipelines, custom CNNs, AlexNet, ResNet experiments, and transfer learning with pretrained models.

---

## 📌 Repository Overview

The repository is organized into four lab folders, each covering a different part of the machine learning and deep learning workflow.

The main goal of these labs was to gain practical experience with:

- PyTorch fundamentals
- Tensor operations and GPU computation
- Dataset preparation and DataLoaders
- Image classification pipelines
- Custom neural network design
- Training and evaluation loops
- CNN architectures
- Hyperparameter experiments
- Transfer learning
- Model visualization and error analysis

---

## 🧪 Labs Included

| Lab | Topic | Main Focus |
|---|---|---|
| **Lab 01** | PyTorch Fundamentals & DataLoaders | Tensor operations, random seeds, GPU tensors, matrix multiplication, dataset loading, transforms, batching |
| **Lab 02** | Custom CNN and AlexNet | Building neural networks from scratch, implementing CNN pipelines, training on image datasets |
| **Lab 03** | ResNet Experiments | Transfer learning / ResNet-based image classification, learning rate and batch-size experiments |
| **Lab 04** | Transfer Learning & Visualizations | Pretrained models, EfficientNet, confusion matrix, most-wrong predictions, Food101 subset experiments |

---

## 🔹 Lab 01 — PyTorch Fundamentals and DataLoaders

This lab focuses on the basics of PyTorch and dataset handling.

### Covered topics

- Creating random tensors
- Matrix multiplication
- Setting random seeds
- GPU computation with CUDA
- Tensor reshaping and squeezing
- Loading image datasets
- Applying transforms
- Creating PyTorch `DataLoader` objects
- Working with batches

### Main files

- `MLDL_Lab01_Ex01.ipynb`
- `MLDL_Lab01_Ex02.ipynb`

---

## 🔹 Lab 02 — Custom CNN and AlexNet

This lab focuses on image classification using convolutional neural networks.

### Covered topics

- Building a custom CNN architecture
- Defining convolutional, pooling, and fully connected layers
- Training a neural network with PyTorch
- Using loss functions and optimizers
- Implementing training and testing loops
- Working with Tiny ImageNet-style image datasets
- Experimenting with AlexNet architecture

### Main files

- `Pytorch_YourModel_exercises.ipynb`
- `Pytorch_AlexNet_exercises.ipynb`

---

## 🔹 Lab 03 — ResNet Experiments

This lab focuses on using ResNet-based models and comparing different training configurations.

### Covered topics

- Using pretrained ResNet models
- Image classification with transfer learning
- Experimenting with different learning rates
- Experimenting with different batch sizes
- Comparing model performance across configurations
- Evaluating training behavior and accuracy

### Example experiment files

- `0.001_16.ipynb`
- `0.001_32.ipynb`
- `0.1_16.ipynb`
- `0.1_32.ipynb`
- `0.1_64.ipynb`

The file names represent different combinations of learning rate and batch size.

---

## 🔹 Lab 04 — Transfer Learning and Visualizations

This lab focuses on transfer learning and visual interpretation of model predictions.

### Covered topics

- Using pretrained `torchvision.models`
- Fine-tuning EfficientNet
- Freezing feature extractor layers
- Replacing classifier layers
- Training on Pizza, Steak, and Sushi image data
- Creating a confusion matrix
- Identifying and visualizing the most incorrect predictions
- Training with a larger subset of Food101
- Comparing different pretrained architectures

### Main file

- `LAB4_MLDL_S327167.ipynb`

---

## 🛠️ Technologies Used

- Python
- PyTorch
- Torchvision
- Torchinfo
- Torchmetrics
- NumPy
- Matplotlib
- ImageFolder
- DataLoader
- CUDA / GPU acceleration
- Jupyter Notebook

---

## 🧠 Key Learning Outcomes

Through these labs, I practiced the complete deep learning workflow:

- Preparing image datasets for training
- Designing and training CNN models
- Using pretrained architectures
- Running hyperparameter experiments
- Evaluating model performance
- Debugging training pipelines
- Interpreting model errors through visualization

These exercises helped strengthen my practical understanding of deep learning implementation in PyTorch.

---

## 📂 Suggested Repository Structure

```text
Machine-Learning-and-Deep-Learning-Labs/
│
├── Lab01_PyTorch_Fundamentals/
│   ├── MLDL_Lab01_Ex01.ipynb
│   └── MLDL_Lab01_Ex02.ipynb
│
├── Lab02_CustomCNN_AlexNet/
│   ├── Pytorch_YourModel_exercises.ipynb
│   └── Pytorch_AlexNet_exercises.ipynb
│
├── Lab03_ResNet_Experiments/
│   ├── 0.001_16.ipynb
│   ├── 0.001_32.ipynb
│   ├── 0.1_16.ipynb
│   ├── 0.1_32.ipynb
│   └── 0.1_64.ipynb
│
├── Lab04_Transfer_Learning_Visualizations/
│   └── LAB4_MLDL_S327167.ipynb
│
└── README.md
```

---

## ▶️ How to Run

1. Clone the repository:

```bash
git clone https://github.com/YasiNoshirvan/REPOSITORY-NAME.git
```

2. Open the notebooks using Jupyter Notebook, JupyterLab, VS Code, or Google Colab.

3. Install the required libraries if needed:

```bash
pip install torch torchvision torchmetrics torchinfo matplotlib numpy
```

4. Run the notebooks cell by cell.

> Some notebooks use GPU acceleration. Running them on Google Colab or a CUDA-enabled machine is recommended.

---

## 📚 Course Information

**Course:** Machine Learning and Deep Learning  
**Institution:** Politecnico di Torino  
**Type:** Practical laboratory exercises  
**Main Framework:** PyTorch

---

## ⚠️ Note

These notebooks were completed as part of university lab exercises.  
They are intended for educational and portfolio purposes and reflect hands-on practice with deep learning workflows.

---

## 📬 Contact

**Yasaman Noshirvanbaboli**  
GitHub: [YasiNoshirvan](https://github.com/YasiNoshirvan)
