# Smokers Status Classification

![GitHub repo size](https://img.shields.io/github/repo-size/ahmedemad2002/Smokers-Status-Classfication)
![GitHub contributors](https://img.shields.io/github/contributors/ahmedemad2002/Smokers-Status-Classfication)
![GitHub stars](https://img.shields.io/github/stars/ahmedemad2002/Smokers-Status-Classfication?style=social)
![GitHub forks](https://img.shields.io/github/forks/ahmedemad2002/Smokers-Status-Classfication?style=social)

## Kaggle Playground Series Competition - S3E24

This repository contains the code and resources developed for the Kaggle competition [Playground Series - S3E24](https://www.kaggle.com/competitions/playground-series-s3e24). The goal of this competition is to classify the smoking status of individuals based on provided data.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Usage](#usage)
- [File Descriptions](#file-descriptions)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction
This project aims to get the highest AUC score possible for classfiying the records from the dataset to smokers or not.

I tested many ML models in this project [LogisticRegression, KNN, RandomForest, XGB].
By testing many Algorithms, found that Random forest and XGB are the best Modles for this problem.


## Dataset

Kaggle inspired the dataset of this competions from [Smoker Status Prediction using Bio-Signals](https://www.kaggle.com/datasets/gauravduttakiit/smoker-status-prediction-using-biosignals) dataset, and used DL to generate new data from it to be the [dataset for the competition](https://www.kaggle.com/competitions/playground-series-s3e24/data).

The training data conatains 24 columns including the target variable *"smoking"*.
All the variables are numeric variables including ints or floats.

## Usage

For using the project and editing it on your local machine, you can follow the following steps.

```bash
# Clone the repository
git clone https://github.com/ahmedemad2002/Smokers-Status-Classfication.git

# Navigate to the project folder
cd Smokers-Status-Classfication

# Install dependencies (if any)
pip install -r requirements.txt
