# Cultural Bias Classification

The goal is to classify items into cultural agnostic and non-agnostic (representative/exclusive) categories using both traditional feature-based methods and transformer-based models.

## Project Structure


`training.ipynb` – Notebook for training both non-LM and LM models

`evaluation.ipynb` – Notebook for loading models and evaluating predictions

`test_output_nonlm.csv` – Predictions from the non-LM classifier on the test set

`test_output_distilbert.csv` – Predictions from the DistilBERT classifier

`test_unlabeled.csv` – Unlabeled test data for inference

`model_stage1_nonlm.pkl` – (Downloadable) Stage 1 non-LM model

`model_stage2_nonlm.pkl` – (Downloadable) Stage 2 non-LM model

`model_distilbert/` – (Downloadable) Folder containing fine-tuned DistilBERT model

## Pretrained models

Due to GitHub's file size limits, the pretrained models can be downloaded from Google Drive: https://drive.google.com/drive/folders/13iyp9ZJQWY7RwlgGZiJ7VUeIOFIqbHmT?usp=sharing


