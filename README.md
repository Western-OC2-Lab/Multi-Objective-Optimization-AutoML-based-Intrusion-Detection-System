# Multi-Objective-Optimization-and-AutoML-based-Intrusion-Detection-System
This repository includes code for the paper "**[Toward Autonomous and Efficient Cybersecurity: A Multi Objective AutoML based Intrusion Detection System](https://ieeexplore.ieee.org/document/11240569/)**" published in **IEEE Transactions on Machine Learning in Communications and Networking (TMLCN)**. In this work, we propose a novel and comprehensive Multi-Objective optimization (MOO) and Automated Machine Learning (AutoML) framework that enables efficient and fully autonomous intrusion detection, especially for IoT systems that need to balance model effectiveness and efficiency/complexity, holding the potential to achieve fully autonomous cybersecurity. To achieve autonomous and efficient intrusion detection, the proposed MOO-AutoML framework automates all critical procedures of the data analytics pipeline, including data pre-processing, feature engineering, model selection, and hyperparameter tuning. 

Authors: Li Yang (liyanghart@gmail.com) and Abdallah Shami  

Organizations: 
- The Advanced Networking Technology and Security (ANTS) Lab, Faculty of Business and IT, Ontario Tech University
- The Optimized Computing and Communications (OC2) Lab, ECE Department, Western University

The paper is publicly available on [IEEE Explore](https://ieeexplore.ieee.org/document/11240569/) and [arXiv](https://arxiv.org/abs/2511.08491)

If you are interested in AutoML and autonomous intrusion detection, below are other comprehensive GitHub repositories:  
1. [AutoML-Implementation-for-Static-and-Dynamic-Data-Analytics](https://github.com/Western-OC2-Lab/AutoML-Implementation-for-Static-and-Dynamic-Data-Analytics)  
2. [AutoML-and-Adversarial-Attack-Defense-for-Zero-Touch-Network-Security](https://github.com/Western-OC2-Lab/AutoML-and-Adversarial-Attack-Defense-for-Zero-Touch-Network-Security)
3. [AutonomousCyber-AutoML-based-Autonomous-Intrusion-Detection-System](https://github.com/Western-OC2-Lab/AutonomousCyber-AutoML-based-Autonomous-Intrusion-Detection-System)

## Abstract of The Paper
With increasingly sophisticated cybersecurity threats and rising demand for network automation, autonomous cybersecurity mechanisms are becoming critical for securing modern networks. The rapid expansion of Internet of Things (IoT) systems amplifies these challenges, as resource-constrained IoT devices demand scalable and efficient security solutions. In this work, an innovative Intrusion Detection System (IDS) utilizing Automated Machine Learning (AutoML) and Multi-Objective Optimization (MOO) is proposed for autonomous and optimized cyber-attack detection in modern networking environments. The proposed IDS framework integrates two primary innovative techniques: Optimized Importance and Percentage-based Automated Feature Selection (OIP-AutoFS) and Optimized Performance, Confidence, and Efficiency-based Combined Algorithm Selection and Hyperparameter Optimization (OPCE-CASH). These components optimize feature selection and model learning processes to strike a balance between intrusion detection effectiveness and computational efficiency. This work presents the first IDS framework that integrates all four AutoML stages and employs multi-objective optimization to jointly optimize detection effectiveness, efficiency, and confidence for deployment in resource-constrained systems. Experimental evaluations over two benchmark cybersecurity datasets demonstrate that the proposed MOO-AutoML IDS outperforms state-of-the-art IDSs, establishing a new benchmark for autonomous, efficient, and optimized security for networks. Designed to support IoT and edge environments with resource constraints, the proposed framework is applicable to a variety of autonomous cybersecurity applications across diverse networked environments.

<p float="left">
  <img src="https://github.com/Western-OC2-Lab/Multi-Objective-Optimization-AutoML-based-Intrusion-Detection-System/blob/main/Framework.jpg" width="500" />
</p>

## AutoML Pipeline and Procedures
1. Automated Data Pre-Processing
   * Automated Normalization based on Min-Max and Z-Score Normalization
   * Automated Hybrid Data Balancing by Combining SMOTE and ADASYN
2. Automated Feature Engineering
   * Optimized Importance and Percentage-based Automated Feature Selection (OIP-AutoFS)
   * Multi-Objective Particle Swarm Optimization (MOPSO)
3. Automated Model Selection
   * LightGBM
   * XGBoost
4. Hyper-Parameter Optimization
   * Optimized Performance, Confidence, and Efficiency-based Combined Algorithm Selection and Hyperparameter Optimization (OPCE-CASH)

### Datasets 
1. CICIDS2017 dataset, a popular network traffic dataset for intrusion detection problems
   * Publicly available at: https://www.unb.ca/cic/datasets/ids-2017.html
2. IoTID20 dataset, a novel IoT botnet dataset
   * Publicly available at: https://sites.google.com/view/iot-network-intrusion-dataset/home

### Code  
* [AutonomousCyber24_Dataset_1.ipynb](https://github.com/Western-OC2-Lab/Multi-Objective-Optimization-AutoML-based-Intrusion-Detection-System/blob/main/MOO_AutoML_Dataset_1.ipynb): code for the sampled CICIDS2017 dataset.  
* [AutonomousCyber24_Dataset_2.ipynb](https://github.com/Western-OC2-Lab/Multi-Objective-Optimization-AutoML-based-Intrusion-Detection-System/blob/main/MOO_AutoML_Dataset_2.ipynb): code for the sampled IoTID20 dataset.

### Requirements  
* Python 3.7+ 
* [scikit-learn](https://scikit-learn.org/stable/)
* [imblearn](https://imbalanced-learn.org/)  
* [Xgboost](https://xgboost.readthedocs.io/en/latest/python/python_intro.html)
* [lightgbm](https://lightgbm.readthedocs.io/en/v3.3.2/Python-Intro.html)

## Contact-Info
Please feel free to contact me for any questions or cooperation opportunities. I'd be happy to help.
* Email: [liyanghart@gmail.com](mailto:liyanghart@gmail.com)
* GitHub: [LiYangHart](https://github.com/LiYangHart), [Western OC2 Lab](https://github.com/Western-OC2-Lab/), and [ANTS-OntarioTechU](https://github.com/ANTS-OntarioTechU)
* LinkedIn: [Li Yang](https://www.linkedin.com/in/li-yang-phd-65a190176/)  
* Google Scholar: [Li Yang](https://scholar.google.com.eg/citations?user=XEfM7bIAAAAJ&hl=en)

## Citation
If you find this repository useful in your research, please cite this article as:  

L. Yang and A. Shami, “Towards Autonomous and Efficient Cybersecurity: A Multi Objective AutoML based Intrusion Detection System,” _IEEE Transactions on Machine Learning in Communications and Networking_, pp. 1–21, 2025, doi: [10.1109/TMLCN.2025.3631379](https://ieeexplore.ieee.org/document/11240569).

```
@ARTICLE{11240569,
  author={Yang, Li and Shami, Abdallah},
  journal={IEEE Transactions on Machine Learning in Communications and Networking}, 
  title={Towards Autonomous and Efficient Cybersecurity: A Multi-Objective AutoML-based Intrusion Detection System}, 
  year={2025},
  pages={1-21},
  keywords={Computer security;Automated machine learning;Optimization;Internet of Things;Intrusion detection;Feature extraction;Data models;Data analysis;Benchmark testing;Adaptation models;Network Automation;AutoML;Multi-Objective Optimization;Cybersecurity;Intrusion Detection System;IoT},
  doi={10.1109/TMLCN.2025.3631379}}
```

