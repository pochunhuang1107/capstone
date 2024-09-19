# Project Idea: Improving Generalization in Predicting Students' Concentration Levels from Wearable Biosignals Using Enhanced Machine Learning Techniques

**CSCI 6806 V4**
**Group 5**

**Group Members**:  
- Po-Chun Huang [p.huang@student.fdu.edu](mailto:p.huang@student.fdu.edu)
- Yunqi Ding [y.ding@student.fdu.edu](mailto:y.ding@student.fdu.edu)
- Lihang Yang [l.yang1@student.fdu.edu](mailto:l.yang1@student.fdu.edu)
- Xinyi Chang [x.chang@student.fdu.edu](mailto:x.chang@student.fdu.edu)

## Project Description
- **Original Paper Overview**: The original study used biosignals (heart rate, conductivity, temperature) from wearables to predict concentration with machine learning, achieving high accuracy for known users but weak performance for unseen users.
- **Problem Statement**: The model's accuracy drops significantly for unseen users due to individual differences in biosignals, limiting its practical application. Additionally, the current models (BRT and CNN) may not be optimal for generalization.
- **Proposed Improvement**: This project will implement user clustering and domain adaptation techniques to enhance the model’s ability to generalize across new users. In addition, we will explore alternative machine learning models to improve prediction accuracy and generalization for unseen users.
- **Impact of Improvement**: The enhanced generalization and the use of optimized machine learning models will make the concentration prediction scalable for a broader population, improving usability in real-world settings like education platforms.

## Project Scope
- Optimize clustering algorithms for user grouping.
- Implement domain adaptation to improve prediction for unseen users.
- Experiment with different ML models to improve accuracy.
- Validate improvements through cross-validation, targeting <20% NMAE for unseen users.

## Novel Aspect
The project introduces clustering, domain adaptation, and exploration of multiple ML models to address the generalization problem and user variability in biosignal-based concentration tracking, which has not been extensively studied in this context.

## Technology Stack
- **Language and Libraries**: Python, Scikit-learn, TensorFlow
- **ML Models**: Random Forest, GBMs, SVM
- **Clustering**: K-means, hierarchical clustering

## Original Paper Reference
C. Södergård and T. Laakko, "Inferring Students’ Self-Assessed Concentration Levels in Daily Life Using Biosignal Data From Wearables," in *IEEE Access*, vol. 11, pp. 30308-30323, 2023, doi: [10.1109/ACCESS.2023.3260061](https://doi.org/10.1109/ACCESS.2023.3260061)
