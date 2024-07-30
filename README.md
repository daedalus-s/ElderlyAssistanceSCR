# Project Lumina: Guiding Light for the Visually Impaired

Project Lumina is an intelligent navigation aid that leverages advanced technologies in robot crowd navigation, human trajectory prediction, and object detection to provide safer and more socially aware guidance for visually impaired individuals.

## Overview

This project aims to enhance the independence and quality of life for visually impaired individuals while promoting more natural human-robot interaction in crowded environments. Our system uses a graph neural network with attention mechanisms to model complex interactions between the user, other pedestrians, and the environment.

## Key Features

- Graph neural network with attention mechanisms for modeling interactions
- Human trajectory prediction for anticipating pedestrian movements
- Object detection using YOLOv3 architecture
- Audio guidance for navigation
- Socially aware navigation that respects personal space and social norms

## Project Structure

1. Data Collection
2. Proxy Solution: Object Detection Module
3. Technology-Only Solution: Complete Navigation Pipeline
4. Socially Cognizant Solution: Enhanced with Human Trajectory Prediction

## Technologies Used

- PyTorch
- YOLOv3
- Recurrent Neural Networks (RNN)
- Graph Neural Networks
- LSTM/GRU for trajectory prediction
- Proximal Policy Optimization (PPO) for reinforcement learning

## Evaluation Metrics

- Success rate
- Collision rate
- Average path length
- Navigation time
- Intrusion ratio
- Minimal distance during intrusions

## Ethical Considerations

We prioritize user privacy, data security, and mitigation of potential biases in our development process. The project adheres to best practices in socially cognizant robotics design.

## Future Work

- Explore more diverse data sources
- Implement advanced deep learning architectures
- Replace bag-of-words with sophisticated text representation techniques
- Conduct extensive real-world testing and validation
