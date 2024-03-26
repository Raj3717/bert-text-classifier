# Topic Modeling using bert-base-uncased

# Overview
This project utilizes the bert-base-uncased model for text classification.

# Directory Structure
1. data: This directory contains data related to the project.
   * bert_base_uncased: This subdirectory holds files related to the BERT model we are using. It contains a pickled file (BertForSequenceClassification_bert_base_uncased.pkl), representing a pre-trained BERT model for sequence classification.
   * data.csv: This CSV file contains the dataset we will use for training and testing the text classifier.
2. download_bert_model.ipynb: This Jupyter Notebook contain code for downloading the BERT base model.
3. bert-retraining.ipynb: This Jupyter Notebook file contains the main code for training the BERT model for text classification. It includes code for data preprocessing, model training and evaluation.
4. using_custom_model.ipynb: This notebook contains demonstrations of how to use the custom finetuned BERT model for text classification.

# Usage

# Prerequisites
You can install the required dependencies by running 'pip install -r requirements.txt'.
