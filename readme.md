# Multiclass Text Classification  
This notebook contains python scripts used in training a multi-level classifier for text classification.
see "Todo.md" for more details.

## Getting started   
### Installation

- Clone repository with HTTPS

    ```bash
     https://github.com/priye-1/Multi-class-prediction-modeling.git
    ```
- create project directory
    ```bash
    mkdir review-predictive-modeling
    ```
-  cd into directory
    
    ```bash
    cd review-predictive-modeling
    ```

- Setup virtual environment with  python venv

    ```bash
    python -m venv .venv
    ```
- Activate the Virtual environment
    ```bash
    source .venv/bin/activate
    ```

- Install requirements

    ```terminal
    # use dev or production requirments depending on location
    pip install -r > requirements.txt
    ```

## Running Scripts
- Download Data - review.csv from link: https://teamqde-my.sharepoint.com/:u:/r/personal/swen_sieben_teamq_de/Documents/reviews.csv.gz?csf=1&web=1&e=1KyzGA
- To run the program, execute each cell on the notebook sequentially

## Recommendation
- The use of additional features like review_summary to train datasets for better prediction
- Carrying out sampling due top data imbalance

## Results
- SVM and Naive Bayes were the two algorithms used. However, SVM had better performance.


## Built with

1) **Python** - Python 3.8


