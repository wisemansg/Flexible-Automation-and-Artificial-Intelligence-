FLEXIBLE AUTOMATION AND ARTIFICIAL INTELLIGENCE (AI)

📘 Module 1 Summary — Automation, Model Estimation and Machine Learning

Module 1 focused on evaluating how different data balancing techniques affect the performance of a machine learning classifier. The dataset consisted of global GDP information from 1960 to 2020, and the goal was to predict the state (region/continent) based on numerical features. The dataset exhibited a significant class imbalance, prompting the need for balancing strategies before model training.

Four balancing approaches were implemented in Python using Random Forest as the classifier:

-Baseline (No Balancing)
-Oversampling (Manual Duplication)
-Undersampling
-Class-Weight Adjustment

After splitting and preprocessing the data, each method was tested and evaluated using accuracy. The results showed that Class-Weight Adjustment provided the best performance, achieving an accuracy of 0.4295, slightly outperforming the baseline and demonstrating improved handling of minority classes. Oversampling provided no meaningful improvement, while undersampling significantly reduced performance due to information loss.

The main takeaway is that adjusting class weights during training is an effective and computationally efficient method for handling imbalanced classification problems without modifying the dataset directly. For future experimentation, the module recommends exploring advanced oversampling techniques such as SMOTE or ADASYN.


🤖 Module 2 Summary — Robotics (Block Manipulation Using P-rob 2)

Module 2 demonstrated the use of the P-rob 2 industrial robot to complete a structured manipulation task involving wooden blocks. The robot was programmed to perform two key operations:

1. Transfer three blocks from one side of a divider to an inclined ramp.
2. Return the blocks and stack them vertically in a stable configuration.

The robot was controlled using Python, leveraging predefined motion paths, gripper commands, and pose transitions. The project emphasized smooth operation, minimal rotation, efficient motion planning, and safe object handling.

Execution was successful across all stages, with the robot performing precise pick, place, and stacking actions without collisions or dropped blocks. The system demonstrated effective path planning, reliable sensor usage, and strong operational consistency. The project highlights the P-rob 2’s suitability for repetitive industrial tasks requiring precision, safety, and structured motion control.

Overall, Module 2 validated that robotics can efficiently automate manipulation tasks with high repeatability, reinforcing their role in modern manufacturing environments.


🤖 Module 3 Summary — Artificial Intelligence in Manufacturing Engineering

Module 3 explored the transformative role of artificial intelligence (AI) in modern manufacturing, highlighting its evolution, applications, benefits, challenges, and future directions. AI has advanced from simple automation to sophisticated machine learning (ML), deep learning, and predictive analytics, enabling smart factories, human-robot collaboration (HRC), and digital twin simulations.

Key Highlights:

AI Evolution & Applications: Predictive maintenance using real-time sensor data to reduce downtime.
Quality control through image and sensor analysis for defect detection.
Robotics and automation, including collaborative robots, to enhance productivity and safety.
Digital twins for virtual testing and optimization of processes.

Technologies & Innovations: Deep learning models (CNNs, RNNs, LSTMs, GANs, Autoencoders) for complex task handling.
Explainable AI (XAI) tools to ensure model transparency and trustworthiness.
Edge AI for real-time decision-making and improved data privacy.
Integration with IoT, SCADA, MES, and Computer Vision Systems for comprehensive data collection and monitoring.

Benefits of AI in Manufacturing: Increased productivity and operational efficiency.
Cost savings through optimized processes and reduced waste.
Improved product quality and real-time defect detection.
Enhanced safety and sustainability, supporting energy efficiency and eco-friendly practices.
Agility in responding to market demands through predictive analytics.

Challenges & Constraints: High initial investment in infrastructure, model development, and training.
Data quality and integration complexities with legacy systems.
Cybersecurity risks and resistance to change among the workforce.
Ethical concerns related to bias, transparency, and responsible AI governance.

Future Directions: Autonomous factories with minimal human intervention.
Advanced predictive maintenance for longer asset life and lower downtime.
Personalized manufacturing driven by real-time AI analytics.
Expansion of collaborative AI systems and edge computing to improve responsiveness and privacy.
Increased focus on sustainability and circular economy practices.

Conclusion:

AI is redefining manufacturing by enabling intelligent, adaptable, and sustainable production environments. While challenges remain, its integration supports the development of flexible, human-centered, and efficient industrial systems, paving the way for a robust, innovative, and sustainable manufacturing future.
