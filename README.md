# SkimLit: Sequential Sentence Classification in Medical Abstracts

## Introduction

This repository contains the implementation and experiments for the NLP model focused on sequential sentence classification in medical abstracts, inspired by the paper "PubMed 200k RCT: a Dataset for Sequential Sentence Classification in Medical Abstracts" ([Link to Paper](https://arxiv.org/abs/1710.06071)).

The dataset used for this project is sourced from [PubMed 200k RCT](https://github.com/Franck-Dernoncourt/pubmed-rct), providing a valuable resource for training and evaluating the model.

## Experiments

### 1. Baseline Model: TF-IDF Classifier

Implemented a baseline model using TF-IDF features for classification.

### 2. Deep Models

Experimented with deep learning models incorporating various combinations of the following components:

- Token embeddings
- Character embeddings
- Pretrained embeddings
- Positional embeddings

## Getting Started

### Prerequisites

- Python
- TensorFlow
- TensorFlow Hub
- Scikit-learn
- Pandas
- NumPy
- Matplotlib