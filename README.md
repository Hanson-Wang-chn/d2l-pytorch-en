# Dive into Deep Learning

## Description

This repository includes public resources of Dive into Deep Learning (D2L), learning schedules and codes for study. 

The original resources can be found [here](https://zh.d2l.ai/index.html). 

## Test Environment

The project has been tested in the following environment.

| Item | Detail |
| ---- | ---- |
| Platform | HP OMEN 17 2022 |
| OS | Ubuntu 20.04 LTS |
| CPU | Intel Core i7-12800HX |
| GPU | NVIDIA GeForce RTX 3080 Ti Laptop (16GB) |
| CUDA | 11.8 |
| Memory | 32GB RAM |
| Disk | 1TB SSD |

## Installation Guide

Enter the project directory, and then create a `conda` environment (recommended):

```bash
    cd path/to/d2l-pytorch-en
    conda create -n d2l-en python=3.10 -y
    conda activate d2l-en
```

Install necessary dependencies:

```bash
    pip install -r requirements.txt
```

**NOTIFICATIONS:**
The official installation instructions [here](https://d2l.ai/chapter_installation/index.html) may lead to several failures. If your CUDA version is not 11.8, install PyTorch from the [official website](https://pytorch.org/get-started/locally/).

Now enjoy the charm of deep learning!
