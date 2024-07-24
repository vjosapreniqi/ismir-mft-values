## Overview
This repository contains the code and data used for in the paper entitled "Automatic Detection of Moral Values in Music Lyrics" accepted to the International Society for Music Information Retrieval Conference (ISMIR) 2024. 
The work involves training BERT models for predicting moral values from song lyrics; generating synthetic lyrics and classifying real-life lyrics using LLMs. 
To reuse the repo install the necessary libraries or run:
``` pip install -r requirements.txt ```

#### 1. BERT_Models
This folder contains Python Jupyter Notebook files for training BERT models and predicting moral values in song lyrics. 
The models are fine-tuned on annotated datasets and are designed to understand and predict the representation of moral values based on the Moral Foundations Theory (MFT).

#### 2. GPT_Models
This folder hosts scripts for lyrics generation and zero-shot classification using GPT models.

#### 3. Lyrics_Data
- MFT_human_annotated_lyrics.csv: This file contains 200 song lyrics annotated by human experts with 10 different MFT values.
- GPT4_generated_songs_with_MFT_values.csv: This file includes 2721 synthetic lyrics with MFT loadings, generated using GPT-4.

