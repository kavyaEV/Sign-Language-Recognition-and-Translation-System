# Sign-Language-Recognition-and-Translation-System
The Sign Language Recognition and Translation System aims to enhance accessibility for the deaf and hard-of-hearing community by providing real-time translation of sign language gestures into spoken and written language. This project integrates Computer Vision (CV) techniques for gesture recognition and Natural Language Processing (NLP)

## Overview

The **Sign Language Recognition and Translation System** is an AI-powered application designed to translate sign language gestures into spoken and written language. This project integrates advanced techniques from Computer Vision (CV) and Natural Language Processing (NLP) to provide an inclusive tool for the deaf and hard-of-hearing community.

## Table of Contents

1. [Overview](#overview)
2. [Model Architecture](#model-architecture)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Results and Evaluation](#results-and-evaluation)
6. [Skills and Technologies Used](#skills-and-technologies-used)
7. [Future Work](#future-work)
8. [License](#license)

## Model Architecture

### Gesture Recognition (CNN)

The gesture recognition component uses a Convolutional Neural Network (CNN) to classify hand gestures from the Sign Language MNIST dataset. The architecture includes multiple convolutional layers for feature extraction, max-pooling layers for dimensionality reduction, and fully connected layers for classification into 25 distinct gesture classes.

### Translation (Transformer-based)

The translation component employs a Transformer-based model (mBART) for sequence-to-sequence translation. It converts recognized gestures into textual representations in a target language. The model leverages an encoder-decoder structure, with self-attention mechanisms to handle long-range dependencies in the input and output sequences.

## Installation

To run this project, you will need to install the necessary dependencies. Use the following commands to set up your environment:

```sh
pip install sentencepiece
pip install transformers
pip install tensorflow
