## NLP on Financial Statements

## AI for Trading Nano Project

In this project, we'll do NLP Analysis on 10-k financial statements to generate an alpha factor.  First, we will convert our corpus of 10-k documents into bag-of-words, and convert them into document vectors using Term-Frequency-Inverse-Document-Frequency (tf-idf) re-weighting. Afterward, we will compute sentiments and similarity metrics. In the end, we’ll then create alpha factors using similarity metrics, then evaluate them using factor-weighted returns, quantile analysis, sharpe ratio, and turnover analysis. For the dataset, we'll be using the end of day from Quotemedia and Loughran-McDonald sentiment word lists.

## Instructions and Install Packages

The Jupyter nodebook must be run under python 3.6.  Type the below commands in the Terminal to  to create and activate a conda environment.

```
conda create -n py36 python=3.6 anaconda
activate py36 #if on Windows
source activate py36 #if on Linux or MacOS
```

Before running `project_5.ipynb`, you need to install all packages in `requirements.txt`.  

### Main Files: Jupyter Structure

```
├── Preprocess the data
    ├── Clean up
    ├── Lemmatize
    └── Remove stopwords
├── Analysis on 10Ks
    ├── Compute bag of words
    ├── Get sentiments
    └── Get document vector: TFIDF
├── Evaluate Alpha Factors
    ├── Create alpha Factors using cosine similarities
    ├── Get factor returns
    ├── Turnover analysis
    └── Sharpe ratio analysis
```

### Authors

Jinjin Liang authored the main functions in `project_5.ipynb`, and this README. All other project files were created by [Udacity](https://www.udacity.com/).

