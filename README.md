# School Coursework

## Table of Contents
- [Introduction](#introduction)
- [Coursework 1: Topic Modelling](#coursework-1-topic-modelling)
- [Coursework 2: CIFAR10 Image Classification](#coursework-2-cifar10-image-classification)
- [Coursework 3: Regression Modelling](#coursework-3-regression-modelling)

## Introduction

## Coursework 1: Topic Modelling

### Project Description
This project focuses on leveraging the advanced capabilities of BERT for the classification of text documents into one of twenty distinct newsgroups. My goal is to fine-tune a pre-trained BERT model to understand and categorize the diverse range of topics covered in this dataset accurately. This approach addresses the challenge of automatically organizing large volumes of text data, facilitating easier access and management of information within these discussion groups.

### Model Architecture
BERT stands out due to its deep understanding of language context and its ability to process words in relation to all the other words in a sentence, rather than one-by-one in order. For this project, I utilized the bert-base-uncased version of BERT, consisting of 12 layers (transformer blocks), 768 hidden units (hidden size), and 12 self-attention heads, totaling 110 million parameters. The model was fine-tuned for the classification task by adding a single linear layer on top of the BERT architecture, which outputs the probabilities for the 20 newsgroup categories. During training, the model weights were adjusted to minimize the classification error on the training dataset, using a combination of the AdamW optimizer and a linear learning rate warm-up schedule.

### Results
The model achieved an accuracy of 86%, with precision, recall, and F1 scores of 86% as well, on the test set.

## Coursework 2: CIFAR10 Image Classification

### Project Description
This project is an exploration into image classificatio using the CIFAR-10 dataset with PyTorch. It aims to develop a convolutional neural network that can accurately classify images into one of the ten categories

### Model Architecture
The model uses a sequence of convolutional layers, ReLU activation functions, max-pooling layers, and fully connected layers to process and classify images.

### Results
The model achieved a classification accuracy of 80% on the test set.

## Coursework 3: Regression Modelling

### Project Description

### Model Architecture

### Results

