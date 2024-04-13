# Lip Reading Deep Learning Model

## Overview
This repository contains a deep learning model for lip reading trained on a custom dataset of over 1000 MPEG files with corresponding alignments for accurate transcription. The model architecture is inspired by the work of Nicholas Renotte and utilizes a combination of 3D convolutional layers, bidirectional LSTM layers, and a Dense layer for character prediction.

## Model Architecture
- **3D Convolutional Layers:** Three 3D convolutional layers are employed to extract spatial-temporal features from the input lip movement data.
- **Bidirectional LSTM Layers:** Two bidirectional LSTM layers are utilized to capture temporal dependencies in both forward and backward directions.
- **Dense Layer:** A Dense layer is employed to predict each character for lip reading.

## Training Details
- **Parameters:** The model consists of approximately 8.4 million parameters.
- **Loss Function:** CTC (Connectionist Temporal Classification) Loss is utilized as the loss function, which allows for sequence labeling without requiring alignment between input and output sequences.

## Acknowledgements
This model is built upon the foundation laid by Nicholas Renotte's project on lip reading. His insights have been invaluable in the development of this project.

## Results
The model achieved the desired results in lip reading tasks, demonstrating its effectiveness in transcribing lip movements to textual representations. Through this project, valuable insights and knowledge were gained, contributing to the advancement of lip reading technology.

## License
This project is licensed under the [MIT License](LICENSE). Feel free to use and modify the code for your own purposes, subject to the terms and conditions of the license.
