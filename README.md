# Machine Learning Project: Diamond Price Prediction

Diamond price prediction is the process of estimating the value or cost of a diamond based on various factors and characteristics. It involves using data analysis, statistical modeling, and machine learning techniques to predict the market price or worth of a diamond.

Diamonds are precious gemstones that are evaluated based on their unique features, known as the "Four Cs": carat, cut, color, and clarity. These factors, along with additional aspects such as depth and table, play a crucial role in determining a diamond's value.

## Requirements

- [sklearn](https://scikit-learn.org/)
- [pandas](https://pandas.pydata.org/)
- [flask](https://flask.palletsprojects.com/)
- [seaborn](https://seaborn.pydata.org/)
- [python](https://www.python.org/)

## Installation and Usage

**Environment Setup:**

```bash
conda create -p venv python==3.8
conda activate venv/
Clone the repository:
git clone https://github.com/swagatabanerjee1904/DiamondPricePrediction

## IN DETAILS:
├──  artifacts
│    ├── preprocessor.pkl
│    ├── model.pkl
│    ├── raw.csv
│    ├── train.csv
│    └── test.csv
│
├──  Logs
│    └── time_format.log
│
├──  notebooks
│    ├── EDA.ipynb
│    ├── Model-training.ipynb
│    └── data
│        └── gemstone.csv
│
├──  prediction_tries
│   ├── prediction.py
│   ├── test_data.csv
│   └── test_pred.csv
│
├── src
│   ├── exception.py
│   ├── logger.py
│   ├── utils.py
│   ├── components
│   │    ├── data_ingestion.py
│   │    ├── data_transformation.py
│   │    └── model_trainer.py
│   ├── pipelines
│   │    ├── prediction_pipeline.py
│   │    └── training_pipeline.py
│
├── static
│   ├── css
│   │    └── styles.css
│   └── images
│        ├── github_logo
│        └── kaggle_logo
│
├── templates
│   └── home.html
│
│
├── application.py
│
└── setup.py




│					
└──setup.py                               - project's metadata and configuration details