# ML-Introduction
This repository contains notebooks for ML Introduction workshop. This workshop is planned as an online event and we will use Zoom as our online conference service.

# Pre-Requistes

Knowledge of python programming languace and basic computer science principles and skills, at a level sufficient to write a reasonably non-trivial computer program. 

Familiarity with linear algebra (matrix operations, differentiation) and probability theory.


# Topics Covered
The main goal of this workshop is to get familiar with ML model building, explore PyTorch framework, and understand how transfer learning works. Although it's impossible to cover all the topics in one workshop session, we believe that the core concepts contained in this workshop are helpful for anyone to get started on ML.


The central activity of the workshop will be around:

1. Introduction to ML
2. What’s Logistic Regression (Why it’s important) 
3. Logistic regression to Neural Nets
4. What are CNNs, RNN, LSTMs, Transformers
5. How to use Transfer Learning

# Logistics

To get started, we recommend using a Jupyter Server from one of the recommended online platforms such as google colab. 

Google Colab - A popular free service from Google with loaded with all the required ML packages. All you need is a browser.


# Setup Instructions for the Workshop 
1.  Open google colab and a new colab notebook with below link (google account credentials needed)

    https://colab.research.google.com/

2. Start typing/ copying below code into the cell

```
from google.colab import drive
drive.mount('/content/drive')
```
3. Start Downloading workshop notebooks to specified directory on google drive.
```
!git clone https://github.com/bharaniabhishek123/ML-Introduction 'drive/My Drive/ML-Introduction'
```

4. change dir 
```
%cd 'drive/My Drive/ML-Introduction'
```