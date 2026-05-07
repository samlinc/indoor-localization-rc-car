# Indoor Localization RC Car

A machine learning project completed at **National Taiwan University ** 
as part of the Mobile and Pervasive Intelligence course.

## Overview

This project explores indoor localization — estimating the real-time position of a 
physical RC car inside a building where GPS is unreliable. The system fuses three 
sensing modalities: **Wi-Fi RSSI**, **Bluetooth Low Energy (BLE)**, and **spectral 
light intensity**, collected via a Raspberry Pi mounted on an Arduino-based smart car.

Three localization models were built, trained, and evaluated: K-Nearest Neighbors (kNN), 
Random Forest (RF), and a custom Fusion Model combining both. The Fusion Model achieved 
the lowest RMSE across all test conditions and was selected for real-time deployment.

## Tech Stack

- **Languages:** Python
- **Hardware:** Raspberry Pi 4B, Arduino Uno, AS7341 Spectral Sensor, HC-05 Bluetooth Module
- **Libraries:** Scikit-learn, NumPy, Pandas, Matplotlib
- **Data Augmentation:** Gaussian Process Regression (GPR), TabGAN, PointGAN
- **Models:** kNN, Random Forest, Fusion Model (kNN + RF)

## Report

The full project report is available here: [:LocalizationReport.pdf](./LocalizationReport.pdf)

## Notes

This was a paired project completed as a final project for a graduate-level course 
at NTU during a semester abroad (Aug – Dec 2025).
