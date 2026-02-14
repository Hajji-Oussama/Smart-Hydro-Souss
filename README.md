# 🌊 Smart-Hydro-Souss: Sovereign Edge AI for Water Resilience

![Project Banner](./assets/project_cover.png)

## 📌 01. Project Vision & Identity
[cite_start]**Smart-Hydro-Souss** is an autonomous engineering ecosystem designed to combat the critical water crisis in the Souss-Massa region, Morocco[cite: 11]. [cite_start]By transforming raw hydraulic telemetry into predictive intelligence, the system eradicates invisible water loss with an accuracy exceeding **95%**[cite: 13].

> [cite_start]**Mission:** To bridge the gap between advanced Digital Infrastructure and sustainable agriculture[cite: 21].

---

## 🏗️ 02. System Architecture & Data Flow
[cite_start]The architecture is built on a high-availability 4-tier stack, ensuring zero-latency at the Edge and robust automation in the Cloud[cite: 56].

![System Architecture](./assest/system_architecture.png)

### 🛠️ The Tech Stack:
* [cite_start]**Edge Layer:** ESP32 Microcontrollers for real-time data acquisition[cite: 67].
* [cite_start]**Connectivity:** Secure MQTT & LoRaWAN protocols for low-power long-range transmission[cite: 64, 65].
* [cite_start]**Automation Engine:** **n8n** (hosted on Ubuntu/Docker) for workflow orchestration and multi-channel alerting[cite: 76, 162].
* [cite_start]**Intelligence:** Custom **LSTM Neural Networks** for temporal pattern recognition[cite: 73, 74].

---

## 🧠 03. AI Engine: Deep Learning Architecture
[cite_start]Our proprietary AI model utilizes a **Multivariate LSTM (Long Short-Term Memory)** network, specifically engineered for hydraulic time-series data[cite: 93, 94].

![AI Engine Logic](./assets/ai_engine_logic.png)

### Key Technical Specs:
* [cite_start]**Temporal Micro-Batching:** Analyzes 30-second sliding windows of Pressure (P), Flow (Q), and Motor Current (I)[cite: 100, 130].
* [cite_start]**Feature Engineering:** Includes synthetic features like Pressure Derivatives ($\Delta P / \Delta t$) to detect the velocity of pipeline bursts[cite: 101, 120].
* [cite_start]**Anomaly Detection Logic:** A final **Sigmoid layer** calculates a probability score[cite: 97]. [cite_start]If the score > 0.85, the system triggers a high-priority emergency response[cite: 92, 98].
* [cite_start]**Explainable AI (XAI):** Integrated **SHAP Values** to explain why a leak was detected (e.g., "15% pressure drop combined with 10% current spike")[cite: 103].

---

## 📊 04. Data Engineering Pipeline
[cite_start]Before reaching the AI, data undergoes a rigorous 3-step cleaning process to ensure 100% reliability[cite: 104, 105].

1.  [cite_start]**Denoising:** Z-Score filtering to remove erratic sensor spikes[cite: 113].
2.  [cite_start]**Missing Value Treatment:** Linear Interpolation to ensure time-series integrity[cite: 114].
3.  [cite_start]**Normalization:** Min-Max Scaling to a [0, 1] range for faster neural convergence[cite: 129].

---

## 📱 05. Interactive Dashboard (UX/UI)
[cite_start]The Android Dashboard provides a real-time "Health Map" of the farm's infrastructure[cite: 131, 153].

![Mobile Dashboard](./assets/mobile_dashboard.png)

* [cite_start]**Real-time Monitoring:** Live telemetry streams directly from field sensors[cite: 153].
* [cite_start]**Financial Reporting:** Automatic calculation of Water and Energy savings in MAD (Dirhams)[cite: 80, 139].
* [cite_start]**Automated Response:** Remote valve control with Biometric Authentication (Fingerprint/FaceID)[cite: 155, 164].

---

## 🔒 06. Security & Scalability
* [cite_start]**End-to-End Encryption:** All data transmitted from ESP32 to the Cloud uses **TLS/SSL**[cite: 162].
* [cite_start]**Microservices Architecture:** Designed to scale across thousands of farms simultaneously across Morocco[cite: 167].
* [cite_start]**Hardware Agnostic:** Compatible with various sensor brands and industrial hardware[cite: 169].

---

## 🗺️ 07. Roadmap 2026-2027
* [cite_start]**Q3 2026:** Pilot launch in 50 farms in **Shtouka Ait Baha**[cite: 172].
* [cite_start]**Q1 2027:** Integration with satellite imagery for regional water stress forecasting[cite: 174].
* [cite_start]**Q4 2027:** AI-driven carbon credit calculation for sustainable farming[cite: 176].

---

## 👨‍💻 Developer & Lead Innovator
**Oussama Hajji**
* [cite_start]2nd-year Digital Infrastructure & Systems Student[cite: 19].
* [cite_start]Expertise: Android Security, AI Integration, & Network Automation[cite: 9, 20].

---
[cite_start]*Building a Water-Resilient Morocco through Sovereign AI Innovation[cite: 181].*
