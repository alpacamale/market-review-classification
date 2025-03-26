# Proejct Overview

This project performs sentiment classifiaction (positive/negative) on online marketplace reviews using a Hugging Face model.  
The model is trained and evaluated to classify Korean product reviews.  
The model used is `beomi/KcELECTRA-base`

## Dataset

데이터셋은 다음과 같이 분류되어있습니다.

| column        | description                               |
| ------------- | ----------------------------------------- |
| first column  | Product rating                            |
| second column | Product review written in Korean language |

## Model Training Process

1. Feature selection
2. Split the dataset into training and test sets
3. Preprocessing data using a tokenizer
4. Train the model
5. Evaluate the model

## Link

[Notebook](notebooks/classification.ipynb)
