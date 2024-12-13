# Network_traffic_classification
## Introduction
- Background:
    - With the rising of IoT trends, the number of network devices has significantly increased, leading to greater heterogeneity in their characteristics.
    - [CIC-IDS 2017 dataset](https://www.unb.ca/cic/datasets/ids-2017.html)
        - This dataset, provided by the Canada Institute for Cybersecurity, serves as a benchmark for evaluating intrusion detection system.
        - This dataset includes both benign and malicious network traffic, labeled with attributes such as timestamp, source/destination IP address, protocol, and more.
- Motivation:
    - Developing an effective intrusion detection system (IDS) faces several challenges:
        - The rapid evolution of attack patterns.
        - The increasing diversity in traffic characteristics among IoT devices.
- Objective:
    - Design an effective scheme to classify benign and malicious network traffic from IoT devices, distinguishing between benign and malicious activities.
## Experiment
- Data collection and preprocessing
- Training Model
## Experiment Result
- Data Preprocessing
    1. Omit features which is not related to flow pattern:
        - flow ID
        - Source IP
        - Source port
        - Destination IP
        - Protocol
        - Time Stamp
    2. undersampling and SMOTE
- training process
- Motivation:
    - Along with the rising of IoT trend the network devices are increagin and more heterogeneous.
