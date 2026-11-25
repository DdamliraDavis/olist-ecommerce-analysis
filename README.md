# Olist Brazilian E-commerce: Marketplace Analysis

Examination project, Data Mining, Modelling and Analytics (MSc Data Science and Analytics).

The notebook `olist_analysis.ipynb` covers:
1. Data exploration and preparation
2. Product categories purchased together (FP-Growth association rules)
3. Seller segmentation (K-means, checked against Ward clustering)
4. Unusual orders (integrity rules, Isolation Forest and Local Outlier Factor)
5. Late-delivery classification and delivery-time regression (time-based validation)

## How to run
1. Python 3.11 or newer (tested with Python 3.13).
2. Download the dataset from https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce and unzip the nine CSV files into a folder named `data/` next to the notebook.
3. Install the dependencies: `pip install -r requirements.txt`
4. Open `olist_analysis.ipynb` and run all cells (about 5 minutes).

The data files are not included in this repository because of their size and licence; they must be downloaded from Kaggle.