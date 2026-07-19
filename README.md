# Image Classification using SwinV2
This repository contains an image classification project developed for the Deep Learning course at Monash University. The project implements a Swin Transformer V2-based classifier and explores modern training strategies including Mixup augmentation and One-vs-All loss. And get Kaggle Ranking Top 10.

## Overview

This project investigates image classification using Vision Transformers.

The main objectives are:

- build an image classification pipeline
- apply modern deep learning techniques
- compare training performance
- evaluate classification accuracy
---

## Features

- Swin Transformer V2 backbone
- Mixup data augmentation
- One-vs-All loss
- PyTorch implementation
- Training and evaluation pipeline
- Performance visualization

## Method

Dataset

    ↓

Preprocessing

    ↓

Swin Transformer V2

    ↓

Mixup

    ↓

OVA Loss

    ↓
    
Prediction

## Dataset

The project uses a multi-class image dataset provided for the Deep Learning course.

Dataset Split

Training:
6500 images

Validation:
500 images

Testing:
16000 images

Number of Classes:
20 ['birds', 'bottles', 'breads', 'butterflies', 'cakes', 'cats', 'chickens', 'cows', 'dogs', 'ducks',
                  'elephants', 'fishes', 'handguns', 'horses', 'lions', 'lipsticks', 'seals', 'snakes', 'spiders', 'vases']

![Classes](docs/images/classes.png)
---


## Results

| Metric | Score |
|---------|------:|
| Accuracy | 97.8% |

---

## Images

![Award](docs/images/award_certificate.png)
![loss](docs/images/loss.png)

## Project Structure

image-classification/

├── README.md
├── notebooks/
├── docs/
---

## How to Run

upload to google colab, and press run all!