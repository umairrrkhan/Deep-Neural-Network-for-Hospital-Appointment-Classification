# Deep-Neural-Network-for-Hospital-Appointment-Classification

This repository builds a neural network classifier to predict hospital appointment no-shows. Improving attendance rates can help hospitals run more efficiently and improve patient health outcomes.

## Introduction

Missed hospital appointments are a major problem for healthcare systems. Accurately forecasting patient no-shows allows hospitals to optimize scheduling, overbook appointments when needed, and identify patients to followup with. This project develops a deep learning model for this prediction task.

## Data

The data is sourced from the [No-show appointments dataset]([https://www.kaggle.com/joniarroba/noshowappointments](https://www.kaggle.com/datasets/joniarroba/noshowappointments)) on Kaggle. It contains over 100k medical appointments from Brazil with features such as:

- Patient demographic information 
- Appointment details
- Disease
- Time deltas between scheduling and appointment day

The notebook covers:

- Importing and exploring the data
- Preprocessing techniques like imputation and normalization 
- Designing and training a neural network
- Evaluating model performance
- Comparing to other models like SVM and logistic regression

## Tools Used

The main libraries used in this project are:

- [Pandas](https://pandas.pydata.org/) for data manipulation
- [Numpy](https://numpy.org/) for numerical processing
- [Scikit-learn](https://scikit-learn.org/stable/) for modeling and evaluation
- [Matplotlib](https://matplotlib.org/) for visualization

## Results

The neural network model achieves:
- 9.98888% accuracy on test set
- 1.00 AUC ROC 
- Solid precision and recall

This shows the promise of using deep learning for modeling hospital appointment adherence. Further work could improve results.

## Contact

For any questions, issues or suggestions, feel free to open an issue or connect with me:

- Email: umairh1819@gmail.com
