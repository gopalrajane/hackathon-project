# Off-Road Semantic Segmentation

A deep learning project for semantic segmentation of synthetic off-road scenes, developed for the Duality AI Offroad Segmentation Challenge.

## Problem

Autonomous vehicles need to identify terrain and obstacles in unstructured environments where conventional road markings are unavailable. The project focuses on preparing simulator-generated segmentation masks and training a model for pixel-level scene understanding.

## Approach

- Remap simulator mask class IDs to a compact label range.
- Prepare image and segmentation-mask data for training.
- Train a DeepLabV3+ model with a ResNet-50 backbone.
- Use a Dice and Focal Loss combination to address class imbalance.
- Generate pixel-wise segmentation predictions.

## Tech Stack

Python, Jupyter Notebook, PyTorch, and computer vision tooling.

## Repository

```text
hackathon-project/
├── train.ipynb
└── README.md
```

## Team

Tech Sorcerer — Aditya Waje, Girish Unde, and Gopal Rajane.

