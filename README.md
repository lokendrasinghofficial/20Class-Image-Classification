# Project 2 – 20 Class Image Classification

This project implements a 20-class image classification system using
ResNet-18 trained from scratch in PyTorch.

## Model
- Architecture: ResNet-18
- Framework: PyTorch
- Classes: 20
- Optimizer: AdamW
- Scheduler: CosineAnnealingLR

## Features
- Custom data augmentation
- Best-model checkpoint saving
- Batch inference on 2000 test images
- Output formatting as required by TA
- Label remapping fix applied

## Output
- Prediction file: 411287098project2.txt
- Corrected file: 411287098_fixed.txt

## Hardware
- Apple Silicon (MPS backend)
