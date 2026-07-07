This project applies unsupervised machine learning to detect fraudulent credit card transactions using the Kaggle Credit Card Fraud Detection dataset. The dataset contains 284,807 transactions made by European cardholders, of which only 492 (0.17%) are fraudulent — making this a heavily imbalanced classification problem.
The core challenge: a model that simply predicts "not fraud" every time would be 99.83% accurate but completely useless. This project addresses that problem head-on.

I have implemented two unsupervised algorithms local outlier factor and isolation forest . This project evaluates both models using precision, recall, F1-score and accuracy — with particular focus on recall, since missing a real fraud case is more costly than a false alarm
