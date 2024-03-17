# IDS-Anta: An open-source code with defence mechanism to detect adversarial attacks for Intrusion Detection System 

This repository comprises the project's "IDS-Anta: An open-source code with defence mechanism to detect adversarial attacks for Intrusion Detection System'. The code and presented model can be utilized in IDS and anomaly detection against adversarial attack scenarios.

This repository presented two intrusion detection system scenarios, with and without adversarial attack, that use four ML and DL-based techniques: Random Forest (RF), Support Vector Machine (SVM), Logistic Regression (LR), and Deep Neural Network (DNN). This study uses preprocessing using z-score normalization and feature extraction employing Singular value decomposition (SVD). The Multi-Armed Bandits (MAB) algorithm is used to select the optimum classifier dynamically, and Thomson sampling is used to balance and enhance the prevalent attack detection rate. Further, the proposed IDS-Anta uses Ant Colony Optimization (ACO) to enhance the model's performance.

This study uses two adversarial attack methods to generate advertised samples: Zeroth Order Optimization (ZOO) and Fast Gradient Sign Attack (FGSM). The study analyzes six evaluation parameters: Accuracy, Detection Rate, Precision, Recall, F-1, and AUC. The proposed model and selected classifiers are tested without adversarial attacks using three benchmark datasets: CIC-IDS-2017, CEC-CIC-IDS-2018, and CIC-DDoS-2019. The outcomes exhibit that all the classifiers performed well without adversarial attacks. 

The proposed IDS-Anta with defence mechanism performed better than the selected four classifiers in this study against both adversarial attack scenarios, i.e., ZOO and FGSM. This outcome signifies that both ML- and DL-based classifiers are suspectable to adversarial attacks.
# Paper Abstract

An intrusion detection system (IDS) is critical to protecting the network from cyber threats. Machine Learning (ML) and Deep Learning (DL)- based IDSs are vulnerable to adversarial attacks due to deliberately framed adversarial samples. To address the issue, this study proposes, IDS-Anta is a Python-based open-source code repository with a powerful defence mechanism to identify adversarial attacks without compromising IDS performance. It uses Multi-Armed Bandits with Thomson Sampling, two adversarial attack generation methods, and three public benchmark datasets. This code repository can be readily applied and replicated on IDS datasets to address the adversarial attack issue.

