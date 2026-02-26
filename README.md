\# NLP Sentiment Model Comparison (CNN · LSTM · BERT)



Notebook-based sentiment analysis project comparing \*\*CNN\*\*, \*\*LSTM\*\*, and \*\*BERT/Transformer\*\* approaches on text datasets (IMDb reviews + ChatGPT-related tweets).  

Focus: preprocessing, model training, and evaluation with standard classification metrics.



\## What I did

\- Built an end-to-end workflow: \*\*EDA → preprocessing → modeling → evaluation\*\*

\- Compared deep learning architectures for sentiment classification:

&nbsp; - \*\*CNN\*\* (feature extraction via convolution)

&nbsp; - \*\*LSTM\*\* (sequence modeling)

&nbsp; - \*\*BERT / Transformers\*\* (context-aware embeddings)

\- Evaluated models using:

&nbsp; - Accuracy, Precision, Recall, F1-score

&nbsp; - Confusion matrix and class distribution analysis



\## Datasets

\- \*\*IMDb movie reviews\*\* (binary sentiment)

\- \*\*ChatGPT-related tweets\*\* (multi-class sentiment such as positive/neutral/negative)



> ⚠️ Note: Raw datasets are \*\*not uploaded\*\* to this repository (size/licensing).  

> Place your local files in the `data/` folder.



\## Repository structure

\- `notebooks/` — all experiments (EDA, preprocessing, training, evaluation)

\- `data/` — local datasets (ignored on GitHub if configured via `.gitignore`)



\## Notebooks (suggested order)

\- `01\_...` EDA and basic inspection

\- `02\_...` preprocessing + cleaning

\- `03\_...` CNN training/evaluation

\- `04\_...` LSTM training/evaluation

\- `05\_...` BERT training/evaluation



\*(Your current filenames are fine too — this is just a recommended ordering.)\*



\## How to run



\### Option A — Google Colab (recommended)

1\. Open any notebook from `notebooks/` in Google Colab

2\. Ensure required libraries are installed (some notebooks may include install cells)

3\. Mount Google Drive (if you keep datasets there) and update paths if needed



\### Option B — Run locally

```bash

python -m venv .venv

\# Windows PowerShell:

.venv\\Scripts\\Activate.ps1



pip install -r requirements.txt

jupyter notebook

