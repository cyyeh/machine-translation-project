# Machine Translation Using Attention Mechanism

## Abstract

This project is about using a sequence-to-sequence model to do a machine translation work. Besides, we use the attention mechanism that can make neural network learn to focus the part of the input that brings better prediction performance.

## Introduction

The image below is the model architecture. If you look at this model using sequence-to-sequence view, Pre-attention Bi-LSTM is the first neural network architecture to deal with the first sequence. Then, we use the attention mechanism to generate adequate output to feed into the second neural network architecture, which deals with the second sequence.

![](images/attn_model.png)