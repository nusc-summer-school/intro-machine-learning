Introduction to Machine Learning NUSC Summer School 2025


Welcome to the Introduction to Machine Learning workshop for the NUSC Summer School 2025! This repository contains all the materials needed to learn machine learning fundamentals.

Workshop Overview
This workshop comprehensively introduces machine learning concepts and practical implementation using Python and scikit-learn. Participants will learn to apply various machine learning algorithms to solve real-world problems.

Learning Objectives
By the end of this workshop, participants will be able to:

Understand the fundamental concepts of machine learning
Differentiate between supervised, unsupervised, and reinforcement learning
Implement standard machine learning algorithms using scikit-learn
Pre-process data for machine learning tasks
Evaluate and interpret model performance
Apply best practices for training and testing models
Prerequisites
Basic understanding of Python programming
Familiarity with numerical Python libraries (NumPy, Pandas)
Understanding of basic statistics concepts
A laptop with Python 3.8+ installed
Workshop Schedule
Day 1: Fundamentals and Supervised Learning
09:00 - 10:30: Introduction to Machine Learning Concepts
10:45 - 12:15: Data Pre-processing and Exploratory Analysis
13:30 - 15:00: Linear Regression and Polynomial Models
15:15 - 16:45: Classification with Logistic Regression and k-NN
Day 2: Advanced Models and Evaluation
09:00 - 10:30: Decision Trees and Random Forests
10:45 - 12:15: Support Vector Machines
13:30 - 15:00: Model Evaluation and Validation
15:15 - 16:45: Feature Selection and Engineering
Day 3: Unsupervised Learning and Applications
09:00 - 10:30: Clustering Algorithms (K-means, Hierarchical)
10:45 - 12:15: Dimensionality Reduction (PCA, t-SNE)
13:30 - 15:00: Real-world Applications and Case Studies
15:15 - 16:45: Final Project and Group Presentations
Setup Instructions
Option 1: Using Conda (Recommended)
bash
## Clone this repository
git clone https://github.com/nusc-summer-school/intro-machine-learning.git
cd intro-machine-learning

## Create and activate conda environment
conda create -n ml-workshop python=3.10
conda activate ml-workshop

## Install required packages
pip install -r requirements.txt
Option 2: Using pip and virtualenv
bash

# Clone this repository
git clone https://github.com/nusc-summer-school/intro-machine-learning.git
cd intro-machine-learning

## Create and activate virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

## Install required packages
pip install -r requirements.txt
Repository Structure
intro-machine-learning/
├── data/                   # Datasets used in the workshop
├── examples/               # Example code and notebooks
├── exercises/              # Hands-on exercises
│   ├── day1/
│   ├── day2/
│   └── day3/
├── presentations/          # Slide decks in PDF format
├── solutions/              # Exercise solutions
├── project/                # Final project template
├── requirements.txt        # Required Python packages
└── README.md               # Workshop information
Datasets
This workshop uses the following datasets:

Housing Price Dataset: Regression task to predict housing prices
Iris Flower Dataset: Classification task to identify flower species
Customer Segmentation Dataset: Clustering task to identify customer groups
All datasets are included in the /data directory and are freely available for educational purposes.


## Recommended Reading:
Géron, A. (2022). Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow. O'Reilly Media.
James, G., Witten, D., Hastie, T., & Tibshirani, R. (2021). An Introduction to Statistical Learning. Springer.


## Online Resources:
Scikit-learn Documentation
Python Data Science Handbook
Kaggle Learn


## Instructors:
Dr. Sarah Johnson - Machine Learning Specialist, University of Cambridge
GitHub | LinkedIn
License
This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments:
We thank all contributors and the NUSC Summer School organizing committee for making this workshop possible.

For questions or additional information, don't hesitate to get in touch with us at info@nuscsummerschool.edu

