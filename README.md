# Data Cleaning for Social Media Dataset

## Overview 

This repository contains Python scripts for cleaning a raw social media dataset. The dataset provided is unstructured and requires multiple cleaning steps before further analysis can be conducted. Data cleaning is a critical preprocessing step in any data pipeline to ensure the quality and usability of the data.

## Data Cleaning Steps

The scripts implement the following cleaning steps, each focusing on a specific aspect of the dataset:

1. Remove Newlines and Tabs:
Newlines and tabs can affect text formatting and need to be eliminated to streamline the dataset.

2. Remove Punctuation, Unicode, and Special Characters:
Punctuation, Unicode symbols, and special characters that are not essential for data analysis are removed to maintain text consistency.

3. Remove Hashtags:
Hashtags are often used in social media posts but may not be useful for specific analyses. The script cleans the dataset by removing all hashtags.

4. Tokenization:
Tokenization is the process of breaking down text into individual words or tokens. This step prepares the data for further natural language processing (NLP) tasks.

5. Remove Stop Words:
Common words such as "the", "is", and "in" add little value to the analysis. The script identifies and removes these stop words to focus on more relevant terms.

## How to Use

Clone this repository and run the Python scripts in sequence to clean the provided social media dataset. Each script corresponds to one of the cleaning tasks listed above. Ensure that all dependencies are installed as specified in the requirements.txt file.
