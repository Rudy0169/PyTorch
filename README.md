🧠 PyTorch Deep Learning Lab
Welcome to my PyTorch learning repository. This project serves as a technical log and playground for mastering deep learning fundamentals, curated by Rudraksh Amar.

📑 Table of Contents
Introduction

Core Learning Modules

Tech Stack

Installation & Setup

Usage

📖 Introduction
This repository is a modular guide to PyTorch. Each notebook is a self-contained experiment focusing on the mathematical theory and practical implementation of neural networks. The goal is to document the journey from Tensor calculus to State-of-the-Art (SOTA) architectures.

🏗️ Core Learning Modules
Notebook	Focus Area	Key Concepts
01_tensor_ops.ipynb	Foundations	Tensor initialization, Broadcasting, Matrix Multiplication
02_autograd.ipynb	Mechanics	Computational Graphs, Chain Rule, .backward()
03_nn_building.ipynb	Architecture	nn.Module, Activation Functions, Loss Functions
04_data_pipeline.ipynb	Engineering	Dataset, DataLoader, Data Augmentation
05_cnn_vision.ipynb	Computer Vision	Convolutions, Pooling, Feature Maps
🛠️ Tech Stack
Language: Python 3.10+

Framework: PyTorch (with CUDA support)

Visualization: Matplotlib, Seaborn

Data Science: NumPy, Pandas, Scikit-learn

⚙️ Installation & Setup
Clone the Project:

Bash
git clone https://github.com/Rudraksh-Amar/pytorch-deep-learning.git
cd pytorch-deep-learning
Environment Setup:

Bash
python -m venv venv
# Windows
venv\Scripts\activate 
# Mac/Linux
source venv/bin/activate
Install Dependencies:

Bash
pip install torch torchvision torchaudio
pip install numpy matplotlib pandas scikit-learn jupyterlab
🚀 Usage
Local Execution

Launch the interactive environment to run experiments:

Bash
jupyter lab
Google Colab

To run these notebooks in the cloud with free GPU access, upload the .ipynb files to Google Colab.
