# Detecting Phishing URLs Using Machine Learning

## Abstract

This project aims to develop machine learning models for detecting phishing URLs with high accuracy, using a variety of classification algorithms. Leveraging the UCI Phishing URL dataset, which contains 51 features extracted from URLs, exploratory data analysis was performed, and several models, including Logistic Regression, Random Forest, Naive Bayes, Support Vector Machines, Decision Trees, and XGBoost, were evaluated based on performance metrics such as accuracy, precision, recall, F1-score, and AUC-ROC curve.

Through dimensionality reduction using Principal Component Analysis (PCA) and addressing challenges like class imbalance, the models demonstrated exceptional performance, with XGBoost achieving the highest accuracy of **99.75%**. The results highlight the effectiveness of machine learning in enhancing cybersecurity by accurately distinguishing between phishing and legitimate URLs, offering a robust solution for preventing phishing attacks.

---

## Results

The accuracy of each model used in detecting phishing URLs is summarized as follows:

| **Model**                  | **Accuracy** |
|----------------------------|--------------|
| XGBoost                   | 99.75%       |
| Random Forest             | 99.70%       |
| Support Vector Machines   | 99.67%       |
| Naive Bayes               | 99.66%       |
| Logistic Regression       | 99.64%       |
| Decision Trees            | 99.45%       |

---

## Conclusion and Future Work

The **XGBoost** model demonstrated the best performance with an accuracy of **99.75%**, indicating its superiority in detecting phishing URLs among all models evaluated.

### Future Work:

- **Feature Engineering**: Explore advanced feature extraction techniques to capture more nuanced patterns in phishing URLs.
- **Deep Learning**: Investigate neural network architectures, such as RNNs or Transformers, for enhanced phishing detection.
- **Real-Time Systems**: Develop a scalable, real-time phishing detection system using the XGBoost model.
- **Adversarial Testing**: Test the model's robustness against adversarial attacks to improve resilience.
- **Deployment**: Integrate the model into a cybersecurity pipeline to provide proactive phishing threat detection.
