# Customer Feedback Sentiment Analysis: BERT vs RoBERTa

This repository evaluates BERT and RoBERTa architectures on customer feedback data, specifically analyzing the impact of sequential context windows on classification performance.

## Project Structure
- \Customer_Feedback_BERT_RoBERTa.ipynb\: Model pipeline, fine-tuning, and evaluation.
- \Dataset-SA.csv\: Raw feedback dataset for sentiment classification.
- \.gitignore\: Prevents large model checkpoints and cache artifacts from being tracked.

## Dependencies
\\\ash
pip install -U transformers datasets accelerate evaluate scikit-learn
\\\

## Architecture & Experimentation
- Baseline: BERT + current review
- Baseline: RoBERTa + current review
- Sequential: BERT + constructed sequential context
- Sequential: RoBERTa + constructed sequential context
