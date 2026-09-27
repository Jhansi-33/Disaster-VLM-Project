# Disaster VLM Project

## Overview

This project explores the use of Vision-Language Models (VLMs) for understanding disaster-related images through Visual Question Answering (VQA).

## Current Work

The initial experiments use SmolVLM-500M-Instruct to analyze disaster images and answer questions about their visual content.

## Current Pipeline

Disaster Image
↓
Vision-Language Model
↓
Visual Question
↓
Generated Answer

## Initial Experiments

The VLM was tested on disaster images using questions related to:

* Disaster type
* Visible objects and structures
* Visible damage
* Presence of people
* Main hazards

## Technologies

* Python
* Google Colab
* PyTorch
* Hugging Face Transformers
* SmolVLM
* Vision-Language Models
* Visual Question Answering

## Future Work

* Integrate the DisasterVQA dataset
* Establish a VLM baseline
* Evaluate VQA performance
* Compare original, degraded, and restored disaster images
* Analyze the effect of image restoration on VLM performance
