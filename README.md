# AI-Powered-Digital-Twin-for-Smart-Battery-Management-in-Renewable-Microgrids

[View PDF directly](https://github.com/Jhoncho517/AI-Powered-Digital-Twin-for-Smart-Battery-Management-in-Renewable-Microgrids/blob/main/AI_Digital_Twin_BMS.pdf)

A CNN-driven digital twin framework for real-time battery State-of-Charge (SOC) and State-of-Health (SOH) estimation, built to improve stability and energy management in renewable microgrids.

> Research poster project — Inamori School of Engineering (Mechanical / Electrical / Renewable Energy Engineering), Alfred University.

---

## Overview

Renewable microgrids powered by intermittent solar and wind suffer from instability, and conventional battery management systems (BMS) lack the real-time optimization and adaptability needed to respond. This research develops an AI-powered **digital twin**  a live virtual replica of a physical battery that uses a Convolutional Neural Network (CNN) to continuously estimate battery health and drive a smart control loop for better efficiency, reliability, and cost-effectiveness.

## Problem Statement

- Renewable microgrids face instability due to intermittent solar/wind generation.
- Traditional battery management lacks real-time optimization and adaptability.
- There is a need for intelligent systems that improve efficiency, reliability, and cost-effectiveness.

## Methodology

The framework follows a five-stage pipeline that connects the physical battery to an AI-driven control loop:

1. **Physical Battery System** — the real cell/pack being monitored.
2. **Data Collection and Processing** — IoT sensors capture voltage (V), current (I), and temperature (T).
3. **CNN Model – Feature Extraction** — learns local patterns (voltage-curve shapes) and temporal dependencies from the sensor data.
4. **Digital Twin** — a virtual model that produces SOC estimation and SOH prediction.
5. **Smart BMS Control Loop** — feeds back into charge optimization, load balancing, and microgrid integration.

## Results

- **SOH prediction** across charge/discharge cycles (Cycle-1, Cycle-84, Cycle-168) tracks the degradation of discharge-voltage curves over test time.
- A **model performance comparison** (radar chart) evaluates CNN, DNN, and traditional machine-learning models across key metrics: prediction accuracy, inference speed, real-time capability, scalability, robustness to aging, and training efficiency.
- The **CNN** shows superior ratings in accuracy, speed, real-time operation, scalability, and robustness.

## Conclusion & Recommendations

- AI-powered CNN digital twins deliver accurate, reliable SOC and SOH estimation, leading to better energy management, longer battery life, and improved microgrid stability.
- Incorporating dynamic battery aging and environmental conditions into the CNN models will increase robustness and adaptability across diverse operating scenarios.
- Deploying optimized, lightweight CNN models on **edge computing** platforms is recommended to enable real-time, efficient monitoring and autonomous control with minimal computational overhead.

## Tech Stack

- **Model:** Convolutional Neural Network (CNN) for feature extraction and SOC/SOH prediction
- **Inputs:** IoT sensor streams — voltage, current, temperature
- **Concept:** Digital twin + smart BMS control loop
- **Target deployment:** Edge computing platforms for real-time inference

## Authors

- **Johnson Jasson** — jjj6@alfred.edu
- **Albert Oganga** — abo2@alfred.edu

Inamori School of Engineering, Alfred University, 14802 NY

## References

1. K. S. S. Alamin, Y. Chen, E. Macii, M. Poncino, and S. Vinco, "A Machine Learning-based Digital Twin for Electric Vehicle Battery Modeling," *2022 IEEE Int. Conf. on Omni-Layer Intelligent Systems (COINS)*, 2022.
2. Hidouri, A., et al. (2024). "Leveraging CNN and SHAP Analysis for Battery SOC Estimation and Anomaly Detection." *ICCS 2024.*
3. Mohammed, H.S., et al. (2024). "Efficient state of charge estimation using CNN-Bi-LSTM hybrid model." *PMC.*
