# Predicting Kickstarter project success with Machine Learning 

By [Su Leen Wong](https://github.com/suleenwong) and [Erick Cantu](https://github.com/eaunaicr97)

![](assets/intro.png)

<sub>Image from [http://clipart-library.com/](http://clipart-library.com/)</sub>

<br>

## Introduction

Kickstarter, founded in 2009, is a crowdfunding platform where project creators can raise money from the public, circumventing traditional avenues of investment. It has an all-or-nothing funding model, whereby a project is only funded if it meets its goal amount; otherwise no money is given by backers to a project.

A huge variety of factors contribute to the success or failure of a project on Kickstarter. Some of these factors are able to be quantified or categorized, which allows machine learning models to predict whether a project will succeed or not. 

The goal of this project is to predict if a Kickstart project will succeed or fail through using Exploratory Data Analysis and supervised Machine Learning models.

More generally, the aim is to help potential project creators as well as potential investors assess what their chances of success on Kickstarter will be.


<br>

## About the data

The dataset contains data on all projects hosted on Kickstarter between the company’s launch in April 2009 until the date of the webscrape on March 14, 2019. The dataset contains 209222 projects.

<br>

## Requirements and Environment

### Requirements:
- pyenv with Python: 3.9.8

<br>

### Environment: 

For installing the virtual environment you can either use the Makefile and run `make setup` or install it manually with the following commands: 

```Bash
pyenv local 3.9.8
python -m venv .venv
source .venv/bin/activate
pip install --upgrade pip
pip install -r requirements.txt
```

## About this repo

In this repository you will find:

- [**column_names.md**](column_names.md) : Descriptions of the columns of the dataset

- **1_Intro_and_Data_Cleaning.ipynb**: Jupyter notebook for introduction to this project, importing the data, combining the csv files and cleaning the data

- **2_EDA_Data_Visualization.ipynb** : Jupyter notebook for Exploratory Data Analysis (EDA) and data visualization

- **03_Modeling.ipynb** : Jupyter notebook with machine learning model implementation and error analysis

- [**Kickstarter_Project_Slides.pdf**](Kickstarter_Project_Slides.pdf): Final presentation of the project

<!-- ## Usage

In order to train the model and store test data in the data folder and the model in models run:

```bash
#activate env
source .venv/bin/activate

python example_files/train.py  
```

In order to test that predict works on a test set you created run:

```bash
python example_files/predict.py models/linear_regression_model.sav data/X_test.csv data/y_test.csv
```

## Limitations

Development libraries are part of the production environment, normally these would be separate as the production code should be as slim as possible. -->
