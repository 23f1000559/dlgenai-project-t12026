# dlgenai-project-t12026

Messy Mashup – Music Genre Classification (Kaggle)

This repository contains my solution for the Messy Mashup Kaggle competition, focused on robust music genre classification under noisy and mixed audio conditions.

## Overview

The goal of this competition is to classify music genres from synthetically generated mashups of audio stems. Unlike traditional classification tasks, the test data introduces multiple real-world challenges:

Instrument stems mixed from different songs
Tempo synchronization across tracks
Varying instrument balances
Additive environmental and synthetic noise

## Problem Statement

Given audio mashups composed of:

drums.wav
vocals.wav
bass.wav
others.wav

…and additional noise samples, the task is to predict one of the following genres:

["blues", "classical", "country", "disco", "hiphop",
 "jazz", "metal", "pop", "reggae", "rock"]
 
## Evaluation Metric

The competition uses Macro F1 Score:

F1 score is computed per class
Scores are averaged equally across all 10 genres
Handles class imbalance effectively

## Repository Structure
├── models/
│   ├── ast/            # MIT AST pretrained model variants
│   ├── cnn/            # Custom CNN architecture
│   ├── xgboost/        # Feature-based XGBoost models
│   └── ...
│
├── report.pdf          # Detailed explanation of methodology
├── requirements.txt    # Python dependencies
├── README.md           

