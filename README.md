
# Flexible Automation and Artificial Intelligence (AI) 🤖⚙️

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Machine%20Learning-FF6F00?logo=scikitlearn&logoColor=white" />
  <img src="https://img.shields.io/badge/Random%20Forest-4CAF50?style=flat" />
  <img src="https://img.shields.io/badge/Robotics-P--rob%202-FF5722?style=flat" />
  <img src="https://img.shields.io/badge/Artificial%20Intelligence-9C27B0?logo=ai&logoColor=white" />
  <img src="https://img.shields.io/badge/Manufacturing-2196F3?style=flat" />
</p>

---

This project explores the integration of **Flexible Automation** and **Artificial Intelligence** through three comprehensive modules covering Machine Learning for imbalanced data, industrial robotics, and the transformative role of AI in modern manufacturing.

## 📘 Module 1 — Automation, Model Estimation and Machine Learning

Module 1 focused on evaluating how different data balancing techniques affect the performance of a machine learning classifier. The dataset consisted of global GDP information from 1960 to 2020, with the goal of predicting the state (region/continent) based on numerical features. The dataset exhibited a significant class imbalance, making balancing strategies essential before model training.

### Balancing Techniques Implemented

Four different approaches were tested using **Random Forest** as the classifier in Python:

- Baseline (No Balancing)
- Oversampling (Manual Duplication)
- Undersampling
- Class-Weight Adjustment

### Key Results

After proper data splitting and preprocessing, each method was evaluated using accuracy:

| Method                      | Accuracy   | Observation                              |
|----------------------------|------------|------------------------------------------|
| Baseline (No Balancing)    | —          | Reference performance                    |
| Oversampling               | —          | No meaningful improvement                |
| Undersampling              | Lower      | Significant performance drop (information loss) |
| **Class-Weight Adjustment**| **0.4295** | **Best performance**                     |

### Main Takeaway

**Class-Weight Adjustment** proved to be the most effective and computationally efficient method for handling imbalanced classification problems. It improved minority class recognition without artificially modifying the dataset.

**Recommendation for future work:** Explore advanced oversampling techniques such as **SMOTE** or **ADASYN**.

---

## 🤖 Module 2 — Robotics (Block Manipulation Using P-rob 2)

Module 2 demonstrated the practical application of industrial robotics using the **P-rob 2** robot to perform a structured block manipulation task.

### Task Description

The robot was programmed to complete two main operations:

1. Transfer three wooden blocks from one side of a divider onto an inclined ramp.
2. Return the blocks and stack them vertically in a stable configuration.

### Technical Approach

- Controlled entirely with **Python**
- Used predefined motion paths, gripper commands, and pose transitions
- Emphasis on:
  - Smooth and efficient motion planning
  - Minimal unnecessary rotation
  - Safe object handling
  - Collision avoidance

### Results

The execution was fully successful:
- Precise pick-and-place operations
- Stable vertical stacking
- No collisions or dropped blocks
- High repeatability and operational consistency

### Conclusion of Module 2

The P-rob 2 successfully demonstrated its suitability for repetitive industrial tasks requiring precision, safety, and structured motion control. This validates the strong role of robotics in modern flexible manufacturing environments.

---

## 🧠 Module 3 — Artificial Intelligence in Manufacturing Engineering

Module 3 provided a comprehensive overview of how Artificial Intelligence is transforming modern manufacturing — from traditional automation to intelligent, adaptive, and sustainable production systems.

### Key Areas Covered

**AI Evolution & Core Applications**
- Predictive maintenance using real-time sensor data
- Automated quality control via computer vision and sensor analysis
- Collaborative robots (Cobots) and human-robot collaboration (HRC)
- Digital Twin technology for virtual simulation and optimization

**Advanced Technologies**
- Deep Learning models (CNNs, RNNs, LSTMs, GANs, Autoencoders)
- Explainable AI (XAI)
- Edge AI for real-time decision making
- Integration with IoT, SCADA, MES, and Computer Vision systems

### Benefits of AI in Manufacturing

- Higher productivity and operational efficiency
- Significant cost reduction and waste minimization
- Improved product quality through real-time defect detection
- Enhanced workplace safety
- Greater sustainability and energy efficiency
- Increased agility to respond to market changes

### Challenges

- High initial investment costs
- Data quality and integration with legacy systems
- Cybersecurity risks
- Workforce resistance to change
- Ethical concerns (bias, transparency, governance)

### Future Directions

- Fully autonomous factories
- Advanced predictive maintenance
- Personalized / on-demand manufacturing
- Expanded collaborative AI and Edge Computing
- Strong focus on sustainability and circular economy

### Final Conclusion of Module 3

Artificial Intelligence is redefining manufacturing by enabling intelligent, flexible, human-centered, and sustainable production systems. Despite existing challenges, AI remains a key driver toward the factories of the future.

---

## 🛠️ Tools & Technologies Used

- **Python**
- **Scikit-learn** (Random Forest Classifier)
- Data Balancing Techniques (Class Weights, Oversampling, Undersampling)
- **P-rob 2** Industrial Robot
- Motion Planning & Gripper Control
- Machine Learning Evaluation Metrics
- Concepts of Deep Learning, Digital Twins, Edge AI, and Explainable AI

---

**Project Status:** Completed  
**Focus Areas:** Flexible Automation • Machine Learning • Industrial Robotics • AI in Manufacturing
```
