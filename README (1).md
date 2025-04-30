# Code Overview: Transformer Models for Biomechanical Pitching Analysis

This directory contains all key model implementations used in the Biomechanical Analysis of Pitchers project. The focus is on using **transformer architectures** to understand baseball pitching mechanics using both sequential and static data.

---

## Contents

### SimpleTransformer.ipynb

A notebook containing baseline model implementations:

- **Baseline Transformer**  
  Processes only sequential biomechanical motion data.

- **Baseline Hybrid Model**  
  Combines sequential motion data and static player features.

- **POI (Player-Only Input) Model**  
  Uses only static inputs like height, weight, etc.  
  Establishes a lower-bound benchmark for comparison.

This notebook was key in validating early architecture decisions and highlighting the importance of combining data types.

---

### DualPathway4.0.ipynb

This Jupyter notebook contains the **final Dual Pathway Transformer architecture** and the **refined hybrid model**. It also includes a pipeline for generating **coaching insights** directly from model predictions.

#### Highlights

- **Dual Pathway Transformer**  
  Separate encoders for mechanical efficiency and force-generation features. These are fused via attention mechanisms, resulting in improved performance and interpretability.

- **Hybrid Model**  
  Integrates time-series biomechanics with static data like height and weight for personalized predictions.

- **Coaching Insight Generator**  
  Translates model outputs into clear, explainable advice for athletes and trainers.
