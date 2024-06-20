# MIRNet Implementation for Low-Light Image Enhancement

This project implements the MIRNet model for enhancing low-light images using the LOL (Low-Light) dataset. MIRNet is a state-of-the-art deep learning model designed to improve image quality by reducing noise, preserving details, and enhancing overall image clarity.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Installation](#installation)


## Introduction

Image restoration aims to recover high-quality images from their degraded versions, which is essential in fields such as photography, security, medical imaging, and remote sensing. Low-light images often suffer from noise, color distortion, and loss of detail due to high ISO settings, long exposure times, and poor lighting conditions. This project utilizes MIRNet to address these issues by learning enriched features that combine contextual information from multiple scales while preserving high-resolution spatial details.

## Dataset

The LOL (Low-Light) dataset is used for training and evaluating the MIRNet model. The dataset contains pairs of low-light and normal-light images, allowing the model to learn the mapping from degraded to enhanced images.
this is the command to integrate the dataset
!wget https://huggingface.co/datasets/geekyrakshit/LoL-Dataset/resolve/main/lol_dataset.zip
!unzip -q lol_dataset.zip && rm lol_dataset.zip



## Installation

To get started, clone this repository and install the required dependencies:

```bash
git clone https://github.com/yourusername/mirnet-lowlight-enhancement.git
cd mirnet-lowlight-enhancement
pip install -r requirements.txt

## Results

![Result 1](https://drive.google.com/uc?export=view&id=1INNkD2996tV4zxLubMzfbGuHOD-9PQQs)

![Result 2](https://drive.google.com/uc?export=view&id=1bkjB3CgpLf6lj9ByFek0OQ8hlktVfZO2)

