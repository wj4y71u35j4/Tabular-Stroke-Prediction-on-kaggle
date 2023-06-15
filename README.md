## Overview

Synthetically-Generated Datasets: Using synthetic data for Playground competitions allows us to strike a balance between having real-world data (with named features) and ensuring test labels are not publicly available. This allows us to host competitions with more interesting datasets than in the past. While there are still challenges with synthetic data generation, the state-of-the-art is much better now than when we started the Tabular Playground Series two years ago, and that goal is to produce datasets that have far fewer artifacts. Please feel free to give us feedback on the datasets for the different competitions so that we can continue to improve!

## Getting Started

1. **Installation**
    - You will need Python 3.6+ installed on your machine. You can download it from [here](https://www.python.org/downloads/).
    - Install the necessary libraries and dependencies using pip:
    
    ```
    pip install -r requirements.txt
    ```

2. **Download the Data**
    - The dataset can be downloaded from [this link](https://www.kaggle.com/competitions/playground-series-s3e2/overview). You will need to have a Kaggle account and be logged in to download the data.

## File Descriptions

train.csv - the training dataset; stroke is the binary target
test.csv - the test dataset; your objective is to predict the probability of positive stroke
sample_submission.csv - a sample submission file in the correct format

## Usage

Simpily run in colab. But you should connect to your own google drive to connect the database

## License

This dataset is distributed under the [Kaggle Dataset Terms of Use](https://www.kaggle.com/terms).
