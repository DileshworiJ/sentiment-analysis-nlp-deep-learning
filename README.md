\# Sentiment Analysis — CNN vs LSTM vs BERT (IMDb + Tweets)



Notebook-based project comparing \*\*CNN\*\*, \*\*LSTM\*\*, and \*\*BERT/Transformers\*\* for sentiment classification on:

\- \*\*IMDb movie reviews\*\* (binary sentiment)

\- \*\*ChatGPT-related tweets\*\* (multi-class sentiment: e.g., positive/neutral/negative)



This repo focuses on \*\*preprocessing → modeling → evaluation\*\* using standard classification metrics.



---



\## What I did

\- Cleaned and prepared text data (tokenization, normalization, optional stopword removal/lemmatization)

\- Trained deep learning models:

&nbsp; - \*\*CNN\*\* for local n-gram feature extraction

&nbsp; - \*\*LSTM\*\* for sequence modeling

&nbsp; - \*\*BERT / Transformers\*\* for contextual embeddings

\- Evaluated using:

&nbsp; - Accuracy, Precision, Recall, F1-score

&nbsp; - Confusion matrix + class distribution checks



---



\## Notebook order (recommended)

Run the notebooks in this order:



1\. \*\*IMDb — CNN/LSTM:\*\* `notebooks/imdb\_cnn\_lstm\_sentimentAnalysis.ipynb`  

2\. \*\*IMDb — BERT:\*\* `notebooks/imdbAnalysis\_BERT.ipynb`  

3\. \*\*Tweets — CNN/LSTM:\*\* `notebooks/tweets\_ cnn\_lstm\_sentimentAnalysis.ipynb`  

4\. \*\*Tweets — BERT:\*\* `notebooks/tweetsAnalysis\_BERT.ipynb`





\## Data

Raw datasets are stored locally in `data/` and are \*\*not uploaded\*\* to GitHub (size/licensing).



---



\## How to run



\### Option A — Google Colab

1\. Open a notebook from `notebooks/` in Colab

2\. Install missing packages if prompted

3\. Set the correct path to your local/Drive `data/` folder

