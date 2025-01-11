# bot-detection-econophysics

This project demonstrates a hybrid approach to detecting social media bots by combining **machine learning algorithms** and **Benford's Law**. Using a Twitter dataset, the analysis identifies behavioral anomalies characteristic of bots. The implementation includes:  

- **Benford’s Law**: Applied to detect statistical irregularities in numerical features like follower counts and tweet activity.  
- **Machine Learning Models**:  
  - **K-Nearest Neighbors (KNN)** for instance-based classification.  
  - **XGBoost** for high-accuracy predictions, achieving an 87% classification rate.  
- **Data Preprocessing**: Feature engineering to extract meaningful patterns, such as tweet description complexity and interaction frequency.  

**Key Features**:  
- Code to preprocess and normalize social media datasets.  
- Implementation of Benford’s Law to analyze and visualize numerical distributions.  
- Comparison of machine learning algorithms (KNN and XGBoost) for bot detection.  
- Insights on improving bot detection accuracy while considering ethical and privacy implications.  

**Key Results**:  
- Benford’s Law revealed clear distinctions between human and bot behaviors.  
- XGBoost outperformed KNN with an accuracy of 87% in identifying bots.  
