# MachineLearning-CreditCardFraud
This project's purpose is to learn marchine learning using a free dataset, to predict credt card fraud.


## Project Overview
This project focuses on detecting fraudulent credit card transactions using a dataset of transactions made by European cardholders in September 2013. The dataset is highly imbalanced, with fraudulent transactions comprising only 0.172% of all data points. The goal is to build a machine learning model capable of accurately identifying fraudulent transactions.


### Dataset Description
- **Source:** Open database from [Kaggle](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud).
- **Features:**
  - `V1, V2, ..., V28`: Principal components obtained via PCA.
  - `Time`: Seconds elapsed between a transaction and the first transaction.
  - `Amount`: Transaction amount, useful for cost-sensitive learning.
  - `Class`: Target boolean variable (0 = Non-fraud, 1 = Fraud).


### Advancement and notes
Follow our advancement and our reflexion with these [notes](https://docs.google.com/document/d/1fePJz0xknhKDkUqOpH21skuunqSc090sFzI-R-MZQwk/edit?usp=sharing).


## Setup and Installation
1. **Clone the Repository:**
    ```bash
    git clone https://github.com/Adri-dou/MachineLearning-CreditCardFraud.git
    ```
2. **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```
3. **Download the Dataset:**
    ```bash
    curl -L -o ~/Downloads/archive.zip https://www.kaggle.com/api/v1/datasets/download/mlg-ulb/creditcardfraud
    ```
    Or download [here](https://www.kaggle.com/api/v1/datasets/download/mlg-ulb/creditcardfraud) the Dataset
    And place it to the root of the project
