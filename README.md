# Megaline User Behavior Classification

## Project Description

Megaline is a mobile company that wants to better understand its customers’ behavior. Many customers are still using legacy plans, and Megaline wants to recommend one of its new plans—**Smart** or **Ultra**—based on user behavior data.

This project aims to develop a classification model that analyzes subscriber behavior and predicts the appropriate plan (Smart or Ultra) for each user with high accuracy.

## Project Folder Structure
│
├── data/                
├── notebooks/           
├── src/                 
├── tests/               
├── README.md            
├── .gitignore           
├── requirements.txt     

## Dataset

The dataset contains monthly behavioral data of users who have already switched to the new plans. The key features include:

- `calls`: Number of calls made
- `minutes`: Total call duration in minutes
- `messages`: Number of text messages sent
- `mb_used`: Internet traffic used in megabytes
- `is_ultra`: Target label (1 for Ultra plan, 0 for Smart plan)

## Objectives

- Explore and preprocess the dataset.
- Split the data into training, validation, and test sets.
- Train classification models and tune hyperparameters.
- Evaluate model performance using accuracy and other relevant metrics.
- Perform sanity checks to ensure model robustness.
