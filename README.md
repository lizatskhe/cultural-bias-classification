# Cultural Bias Classification

The goal is to classify items into cultural agnostic and non-agnostic (representative/exclusive) categories using both traditional feature-based methods and transformer-based models.

**Cultural Agnostic (CA)**: Universally known items not tied to any culture (e.g., bicycle, smartphone).

**Cultural Representative (CR)**: Items associated with a culture but understood more broadly (e.g., sushi, pizza).

**Cultural Exclusive (CE)**: Culturally specific items with limited recognition outside their origin (e.g., Nowruz, kimono).

## Methods

For the **non-LM-based** approach, I performed feature engineering using metadata fields (e.g., category, subcategory), applied text preprocessing, and trained a Random Forest classifier with class balancing and error analysis.

For the **LM-based** approach, I fine-tuned a DistilBERT model on combined textual fields, using class weights to address imbalance and evaluated performance using accuracy and F1-score.

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


