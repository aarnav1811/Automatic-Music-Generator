# Automatic Music Generator Using LSTM

This project implements an automatic music generator using Long Short-Term Memory (LSTM) neural networks. It takes already composed music samples as input and generates a completely new music piece as output.

## Table of Contents

1. [Introduction](#introduction)
2. [Features](#features)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Input Format](#input-format)
6. [Output Format](#output-format)
7. [Contributing](#contributing)
8. [License](#license)

## Introduction

This project leverages LSTM neural networks to create an automatic music generation system. By training on pre-existing music samples, the model learns musical patterns and generates new, original compositions. LSTMs are well-suited for this task due to their ability to capture long-term dependencies in sequential data, making them ideal for music generation.

## Features

- **Training on Existing Music Samples**: The model is trained on a dataset of composed music pieces.
- **Music Generation**: Generates new music pieces that capture the style and structure of the training data.
- **MIDI Output**: The generated music is saved in MIDI format, which can be played back using various music software.
