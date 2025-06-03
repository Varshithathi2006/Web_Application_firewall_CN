# Web_Application_firewall_CN
# 🛡️ Web Application Firewall using LSTM

A hybrid machine learning-based Web Application Firewall (WAF) designed to detect and mitigate DDoS, SQL Injection, and XSS attacks. Developed for the course "Introduction to Computer Networks-I", this project implements a two-layer detection system that combines heuristic rules with deep learning (LSTM) to defend web applications in real-time.

## 📌 Project Overview

Web applications are vulnerable to complex threats like:
- **Distributed Denial of Service (DDoS)**
- **SQL Injection**
- **Cross-Site Scripting (XSS)**

Traditional rule-based firewalls often fail to detect evolving patterns. This WAF uses:
- Heuristic filtering for fast rejection
- LSTM models for sequence-based deep analysis

## 👨‍💻 Team Members

- **Varshitha Thilak Kumar** - CB.SC.U4AIE23258  
- **Siri Sanjana S** - CB.SC.U4AIE23249  
- **Shreya Arun** - CB.SC.U4AIE23253  
- **Anagha Menon** - CB.SC.U4AIE23212  

### 🧑‍🏫 Guided By:
**Mr. Jaisooraj J**  
Centre for Computational Engineering and Networking  
Amrita School of Artificial Intelligence

## 🧠 Methodology

1. **Preprocessing**:
   - DDoS: Numerical features like packet size, request count
   - SQLi/XSS: Tokenized input strings
2. **Model Training**:
   - Separate LSTM models for DDoS, SQL Injection, XSS
3. **Dual-Layer Detection**:
   - Layer 1: Heuristic rules
   - Layer 2: LSTM model validation
4. **Evaluation**:
   - Metrics: Precision, Recall, F1-Score

## 📊 Results

- ✅ DDoS detection accuracy: **98%**
- ✅ SQL Injection & XSS: High consistency on obfuscated inputs
- ✅ Precision and recall values demonstrate effective classification with minimal false positives

## ⚙️ Technologies Used

- Python (NumPy, Pandas)
- Keras/TensorFlow for LSTM models
- Data preprocessing for both numerical and text inputs

## 🔮 Future Scope

- Add real-time anomaly detection
- Integrate advanced NLP techniques
- Expand dataset for more robust zero-day threat detection
- Improve false-positive reduction with threshold tuning


