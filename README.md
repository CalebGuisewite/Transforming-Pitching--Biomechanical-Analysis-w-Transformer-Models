# Transforming-Pitching--Biomechanical-Analysis-w-Transformer-Models

# Biomechanical Analysis of Pitchers Using Transformer Models

A deep learning approach to understanding and evaluating baseball pitching mechanics using transformer architectures and motion capture data.

## Overview

This project implements advanced machine learning techniques to analyze the biomechanics of baseball pitchers. Leveraging **transformer models**—deep neural networks known for their effectiveness in handling sequence data—the project processes **multidimensional time-series motion capture data** to uncover insights about pitching performance.

The aim is to evaluate how well transformer architectures can learn and generalize subtle patterns in sequential biomechanical data, with the broader goal of integrating these insights into **player development and predictive analytics** in baseball.

The project shows how biomechanical data can be introduced into predictive sports analytics.

## Objectives

-  Apply transformer models to sequential biomechanical motion data
-  Test a transformer model's ability to understand biomechanical data for the prediction of velocity
-  Explore the translation of model outputs into **practical feedback for coaching**
-  Explore how biomechanical data might enhance baseball performance analytics

## Key Contributions

- Introduces **transformer-based deep learning** to the field of sports biomechanics
- Demonstrates the feasibility of AI-assisted motion analysis for athletes
- **Demonstrates the possibility of biomechanical data being introduced into predictive sports analytics**
- Bridges **sports science, machine learning, and player development**

## Methodology

1. **Data Collection**
   - 3D motion capture of pitching mechanics
   - Structured as multivariate time-series (e.g., joint angles, velocities)

2. **Data Preprocessing**
   - Normalization, windowing, temporal alignment

3. **Model Architecture**
   - Transformer encoder with positional encoding
   - Attention mechanisms to capture inter-joint and temporal dependencies

4. **Training & Evaluation**
   - Model trained on labeled biomechanical sequences
   - Performance assessed via accuracy, interpretability, and generalizability

## Tech Stack

| Component     | Description                         |
|---------------|-------------------------------------|
| Python        | Core programming language           |
| PyTorch       | Deep learning framework             |
| NumPy/Pandas  | Data processing                     |
| Matplotlib    | Visualization                       |
| Jupyter Notebooks | Experimentation & documentation |


## Insights & Applications

- **Demonstrated that using a domain and sport-specific architecture can increase the performance of the model** 
- Showed that transformer models can understand the subtle patterns of pitching mechanics
- Translated attention weights into visualizations to highlight key movement phases
- Demonstrated how AI can assist coaches in providing evidence-based feedback

## Model Improvements
One of the most impactful innovations in this project was designing a dual-pathway transformer architecture. Instead of feeding all biomechanical features into a single stream, the model processes:
- Mechanical efficiency features (e.g., joint angles, landmarks)
- Force generation features (e.g., force moments, joint velos)

These are encoded through separate transformer branches and later fused. This architecture significantly improved the model's ability to detect nuanced movement patterns, leading to better generalization.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

- Belmont University — Senior Capstone Project (Spring 2025)  
- Dr. Christina Davis — Project Supervisor  
- The OpenBiomechanics Project — Dataset resource  
- My own experience as a former collegiate baseball player
