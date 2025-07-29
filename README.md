# GCD-GNN
# SecureKey: GC-GNN-Powered Fraud Detection System for Mobile Banking

🚧 **Status: In Progress**  
🛠️ **Platform**: Android Studio (Java)  
🧠 **Machine Learning Model**: GCD-GNN (Global Confidence Degree Graph Neural Network)  
🔐 **Application Domain**: Mobile Banking Security & Fraud Detection

## 🧩 Project Overview

This project aims to integrate machine learning into mobile banking security, particularly using a **GCD-GNN** model to detect fraudulent transactions. The solution is built as an Android mobile application developed in **Java**, with the backend logic leveraging pre-trained models or APIs to assess transaction legitimacy in real-time.

## 🎯 Objectives

- Detect fraudulent transactions in mobile banking using graph-based machine learning.
- Integrate **intelligent authentication mechanisms** such as:
  - Behavioral biometrics
  - Multi-factor authentication (e.g., CCCD chip ID, VNeID, IMEI, PIN, Smart OTP)
- Offer a personalized fraud detection experience for specific user segments (e.g., university students).
- Develop a user-friendly and secure mobile interface for real-world usage scenarios.

## 🔍 Key Features (Planned)

- [x] Data pre-processing for transaction graph construction
- [x] Embedding generation and GCD-GNN model training (via Google Colab)
- [ ] Fraud detection module in Android (Java) – *In Progress*
- [ ] Integration of smart authentication methods
- [ ] Real-time transaction evaluation & risk scoring
- [ ] Alert system for abnormal activity

## 🧠 About GCD-GNN

**GCD-GNN** is a fraud detection model that combines both local (neighbor-based) and global (prototype similarity) features in a graph neural network. It uses a novel mechanism called **Global Confidence Degree** to weigh message-passing contributions from typical and atypical neighbors—thus improving detection accuracy while remaining lightweight for deployment.

> Learn more in our paper: *“Chìa khóa bảo mật: Giải pháp phát hiện gian lận bằng phương pháp học máy và xác thực thông minh cho giao dịch Mobile Banking”* (2025)

## 📱 Mobile Implementation

The mobile app is being developed using **Android Studio (Java)**. It will feature:
- Login and secure authentication screen
- Transaction monitoring interface
- Risk assessment and fraud alert features
- Backend integration with GCD-GNN model hosted externally (e.g., Flask API or embedded ML)

## 📁 Repository Structure

