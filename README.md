# Inverse Dynamics Modeling Using Deep Learning
This project demonstrates a deep learning–based inverse dynamics model implemented using convolutional neural networks (CNNs). 
The notebook explores model training, evaluation, and prediction behavior, and is inspired by recent research directions in 
robotics and embodied AI, including concepts discussed in NVIDIA’s Project GR00T.
## Project Overview
Inverse dynamics modeling focuses on predicting the control actions or forces required to produce a desired motion or state change. 
Such models are widely used in robotics, control systems, and embodied AI to enable agents to interact effectively with their environment.

This project presents a deep learning–based approach to inverse dynamics using convolutional neural networks (CNNs). 
The notebook walks through data preparation, baseline evaluation, model training, and prediction analysis to demonstrate 
how neural networks can learn complex state–action relationships.
## Dataset

This project uses data derived from the EPIC-KITCHENS dataset, a large-scale egocentric video 
dataset commonly used for research in action understanding, robotics, and embodied AI.

The dataset provides sequences representing observed states and corresponding actions, which 
are suitable for learning inverse dynamics relationships. In this project, the data is used to:
- Establish baseline (pre-learning) behavior
- Train deep learning models on state–action mappings
- Evaluate prediction quality before and after training

## Methodology

The notebook explores multiple deep learning architectures to model inverse dynamics and 
compare their learning behavior and predictive performance.

### Models Implemented
- **Baseline Model:**  
  Used to evaluate system behavior before learning and establish a reference performance level.

- **Convolutional Neural Network (CNN) Model 1:**  
  A CNN-based inverse dynamics model trained to learn the mapping between system states and 
  required control actions.

- **Convolutional Neural Network (CNN) Model 2:**  
  A modified CNN architecture designed to compare performance and stability against the first model.

### Training & Evaluation
- Data split into training and testing sets
- Model performance evaluated before and after training
- Predictions analyzed to assess how well each model captured system dynamics
## Results & Observations
- The baseline model demonstrated limited ability to predict control actions accurately, 
  serving primarily as a reference for pre-learning system behavior.
- Both CNN-based models showed clear improvement after training, indicating that the neural 
  networks successfully learned inverse dynamics relationships from the data.
- Differences in prediction stability and accuracy were observed between the two CNN architectures, 
  highlighting the impact of architectural choices on model performance.
- Trained models produced more consistent and realistic predictions compared to the untrained baseline.
  ## Tech Stack
- Python
- Deep Learning
- Convolutional Neural Networks (CNNs)
- Jupyter Notebook
- NumPy
- PyTorch / TensorFlow (as used in the notebook)
## How to Run
1. Clone the repository
2. Open the Jupyter Notebook
3. Install required Python dependencies
4. Run the notebook cells sequentially to reproduce the results
## Notebook
- `Deep Learning DEMO.ipynb` — Complete implementation and experimentation notebook
## Inspiration & Credits
This project is inspired by research directions in robotics and embodied AI, including 
concepts discussed in NVIDIA’s Project GR00T. This repository is an educational and 
experimental demo and is not an official reproduction of any NVIDIA research.

