# IDS-Anta: An open-source code with defence mechanism to detect adversarial attacks for Intrusion Detection System 

This repository comprises the project's "IDS-Anta: An open-source code with defence mechanism to detect adversarial attacks for Intrusion Detection System'. The code and presented model can be utilized in IDS and anomaly detection against adversarial attack scenarios.

This repository presented two intrusion detection system scenarios, with and without adversarial attack, that use four ML and DL-based techniques: Random Forest (RF), Support Vector Machine (SVM), Logistic Regression (LR), and Deep Neural Network (DNN). This study uses preprocessing using z-score normalization and feature extraction employing Singular value decomposition (SVD). The Multi-Armed Bandits (MAB) algorithm is used to select the optimum classifier dynamically, and Thomson sampling is employed to balance and enhance the prevalent attack detection rate. Further, the proposed IDS-Anta uses Ant Colony Optimization (ACO) to enhance the model's performance.

This study uses two adversarial attack methods to generate advertised samples: Zeroth Order Optimization (ZOO) and Fast Gradient Sign Attack (FGSM). The study analyzes six evaluation parameters: Accuracy, Detection Rate, Precision, Recall, F-1, and AUC. The proposed model and selected classifiers are tested without adversarial attacks using three benchmark datasets: CIC-IDS-2017, CEC-CIC-IDS-2018, and CIC-DDoS-2019. The outcomes exhibit that all the classifiers performed well without adversarial attacks. 

The proposed IDS-Anta with defence mechanism performed better than the selected four classifiers in this study against both adversarial attack scenarios, i.e., ZOO and FGSM. This outcome signifies that both ML- and DL-based classifiers are suspectable to adversarial attacks.
# Abstract

An intrusion detection system (IDS) is critical to protecting the network from cyber threats. Machine Learning (ML) and Deep Learning (DL)- based IDSs are vulnerable to adversarial attacks due to deliberately framed adversarial samples. To address the issue, this study proposes, IDS-Anta is a Python-based open-source code repository with a powerful defence mechanism to identify adversarial attacks without compromising IDS performance. It uses Multi-Armed Bandits with Thomson Sampling, two adversarial attack generation methods, and three public benchmark datasets. This code repository can be readily applied and replicated on IDS datasets to address the adversarial attack issue.

# Research Questions

•	What is the general procedure for ML- and DL-based IDS design, including the significance of preprocessing and feature extraction?

•	How can we use MAB with Thomson Sampling to dynamically choose an effective classifier and balance and enhance the attack detection rate?

•	How can use ZOO and FGSM to generate adversarial attacks?

•	How can we enhance IDS performance in detecting adversarial attacks with combined methods (i.e., proposed IDS-Anta)?


# A high-level overview of the IDS-Anta code repository 







![image](https://github.com/kousikbarik/lab-ids-anta/assets/91803246/e0ea284b-ef2b-4c44-ade0-1ca6a48d9d41)




Fig. A high-level overview of the IDS-Anta code repository 


![image](https://github.com/kousikbarik/lab-ids-anta/assets/91803246/7a3aad05-b4ea-4607-bb6f-183c7479ede0)

Fig. IDS-Anta architecture 


# Dataset and Implemenation 

# Dataset

The CIC-IDS-2017 is a popular publicly available dataset for IDS. (https://www.unb.ca/cic/datasets/ids-2017.html)

The CSE-CIC-IDS2018  is a publicly available dataset for IDS.(https://www.unb.ca/cic/datasets/ids-2018.html)

The CCIC-DDoS2019  is a publicly available dataset for DDoS.(https://www.unb.ca/cic/datasets/ddos-2019.html)

# Code

ML-DL-IDS-Anta-without-adversarial.ipynb: code for evaluating IDS with MAB and Thomson sampling without adversarial attack samples. 

ZOO-adversarial-samples.ipynb: code for evaluating the IDS classifiers and IDS-Anta with a defence mechanism for the ZOO adversarial attack scenario.

FGSM-adversarial-samples.ipynb : code for evaluating the IDS classifiers and IDS-Anta with an FGSM adversarial attack scenario with defense mechanism.

# Algorithims

 Random Forest (RF)
 
 Support Vector Machine (SVM)
 
 Logistic Regression (LR)
 
 Deep Neural Network (DNN)

 Singular value decomposition (SVC) 

 Multi-Armed Bandits (MAB)

  Ant Colony Optimization (ACO)


# Additional Readings

Paya, A., Arroni, S., García-Díaz, V., & Gómez, A. (2024). Apollon: A robust defense system against Adversarial Machine Learning attacks in Intrusion Detection Systems. Computers & Security, 136, 103546.

Baniecki, H., & Biecek, P. (2024). Adversarial attacks and defenses in explainable artificial intelligence: A survey. Information Fusion, 102303.

Zhang, A., Ran, Y., Tang, W., & Wang, Y. G. (2024). Vulnerabilities in video quality assessment models: The challenge of adversarial attacks. Advances in Neural Information Processing Systems, 36.

Wei, H., Zhang, K., Zhang, H., & Shi, Y. (2024). Resilient and constrained consensus against adversarial attacks: A distributed MPC framework. Automatica, 160, 111417.






# Contact Details

Please feel free to contact us with any queries or cooperation prospects.

Email: sanjay.misra@ife.no

