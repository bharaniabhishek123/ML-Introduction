# ML-Introduction
This repository contains notebooks for ML Introduction workshop. This workshop is planned as an online event and we will use Zoom as our online conference service.

# Pre-Requistes

Knowledge of python programming languace and basic computer science principles and skills, at a level sufficient to write a reasonably non-trivial computer program. 

Familiarity with linear algebra (matrix operations, differentiation) and probability theory.


# Logistics / Setup Instructions

To get started, we recommend using a Jupyter Server from one of the recommended online platforms such as google colab. 

Google Colab - A popular free service from Google with loaded with all the required ML packages. All you need is a browser.


# Setup Instructions for the Workshop 
1.  Open google colab and a new colab notebook with below link (google account credentials needed)

    https://colab.research.google.com/

    Create a new colab notebook and go to the first cell inside the notebook :



2. Start typing/ copying below code into the cell

```
from google.colab import drive
drive.mount('/content/drive')
```
Click on the below url the and it will ask you to Sign in (click on Sigh in to continue) 
```
Go to this URL in a browser: https://accounts.google.com/o/oauth2/auth?client_id=947318989803-6bn6qk8qdgf4n4g3pfee6491hc0brc4i.apps.googleusercontent.com&redirect_uri=urn%3aietf%3awg%3aoauth%3a2.0%3aoob&scope=email%20https%3a%2f%2fwww.googleapis.com%2fauth%2fdocs.test%20https%3a%2f%2fwww.googleapis.com%2fauth%2fdrive%20https%3a%2f%2fwww.googleapis.com%2fauth%2fdrive.photos.readonly%20https%3a%2f%2fwww.googleapis.com%2fauth%2fpeopleapi.readonly%20https%3a%2f%2fwww.googleapis.com%2fauth%2fdrive.activity.readonly%20https%3a%2f%2fwww.googleapis.com%2fauth%2fexperimentsandconfigs%20https%3a%2f%2fwww.googleapis.com%2fauth%2fphotos.native&response_type=code
```

Copy the code and paste it inside the `Enter your authorization code:` on the original tab and hit enter.


3. In this step, we are cloning the github repository to your google drive.Start Downloading workshop notebooks to specified directory on google drive.

On the next cell copy the below git command 

```
!git clone https://github.com/bharaniabhishek123/ML-Introduction 'drive/My Drive/ML-Introduction'
```

![plot] (./gdrive_after_clone.png)


4. change dir 
```
%cd 'drive/My Drive/ML-Introduction'
```


# Topics Covered
The main goal of this workshop is to get familiar with ML model building, explore PyTorch framework, and understand how transfer learning works. Although it's impossible to cover all the topics in one workshop session, we believe that the core concepts contained in this workshop are helpful for anyone to get started on ML.


The central activity of the workshop will be around:

1. Introduction to ML
2. What’s Logistic Regression (Why it’s important) 
3. Logistic regression to Neural Nets
4. Define our first NN and train a classifier
5. Use Transfer Learning to fine tune a model. 
