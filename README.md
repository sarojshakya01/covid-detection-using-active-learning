# COVID-19 Detection using DAgger Imitation Learning

This project leverages imitation learning, specifically the DAgger algorithm, to detect COVID-19 from various data sources. The goal is to improve the accuracy and robustness of COVID-19 detection models using advanced machine learning techniques.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Model Training](#model-training)
- [Evaluation](#evaluation)
- [Results](#results)
- [Contributing](#contributing)

## Introduction
The COVID-19 pandemic has necessitated rapid advancements in diagnostic tools. This project explores the use of imitation learning, particularly the DAgger algorithm, to enhance the detection of COVID-19 from medical images and other related data.

## Dataset
The datasets used in this project include:
1. **Chest X-ray images** from the [COVID-19 Radiography Database](https://www.kaggle.com/tawsifurrahman/covid19-radiography-database).
2. **CT Scan images** from the [UCSD-AI4H COVID-CT Dataset](https://github.com/UCSD-AI4H/COVID-CT/tree/master/Data-split).

## Installation
To get started, clone the repository and install the necessary dependencies:

```bash
git clone https://github.com/sarojshakya01/covid-detection-using-active-learning.git
cd covid-detection-using-active-learning
pip install -r requirements.txt
```

## Usage
After installation, you can use the notebook file to preprocess data, train models, and evaluate performance:

## Model Training
The training process involves using the DAgger algorithm to iteratively refine the model. The configuration file `config.yaml` allows you to specify hyperparameters and other settings.

## Evaluation
Model evaluation is performed on a separate test set. Metrics such as accuracy, precision, recall, and F1-score are computed to assess performance.

## Results
The results of the model training and evaluation are stored in the specified directory. Detailed performance metrics and visualizations can be found in the evaluation report.

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request with your changes. Ensure that your code adheres to the project's coding standards and includes appropriate tests.

