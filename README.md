# Research-Overview.github

**Project Overview**

TrustiPay is an AI-powered digital payment platform built for the Sri Lankan financial ecosystem, offering secure, inclusive, real-time, multilingual, and offline-enabled transactions. Its main goal is to increase trust and adoption of digital payments by reducing fraud and security risks through machine learning–based fraud detection and transaction surveillance.

The Voice-Controlled UX & Inclusive Interfaces component improves accessibility by enabling Sinhala/Tamil voice payments, voice-biometric authentication, multilingual interfaces, and offline access through USSD, SMS, and IVR—supporting low-literacy users and feature-phone users with secure, simple interactions.

The AI-Powered Fraud Detection & Transaction Surveillance component is the system’s security layer, monitoring transactions across online, offline, peer-to-peer, and voice channels. It uses risk scoring to approve transactions, trigger OTP/biometric challenges, or block suspicious activity, while maintaining audit-ready logs and compliance support.

The Resilient Money Movement & Offline Value (RMMOV) component enables offline-first peer-to-peer payments using Bluetooth, Wi-Fi Direct, QR codes, and optional audio signals. It secures transactions using cryptographic signing and a hash-chained local ledger to prevent double spending, then synchronizes with the backend once connectivity returns.

The AI-Based User Behavior Analytics & Financial Profiling component adds financial intelligence by analyzing transactions and SME cash flows to generate Responsible Spending Scores, creditworthiness insights, and personalized nudges, helping users make better decisions while supporting risk assessment and inclusion.


**Project Dependencies**

At the application layer, Flutter (Dart) is a core dependency used to build cross-platform mobile applications with multilingual UI support, offline storage, and voice-enabled interactions. Feature-phone access depends on telecom technologies such as USSD, SMS, IVR, and DTMF, integrated via local telco APIs or cloud telephony gateways.For backend services and AI processing, TrustiPay relies heavily on Python-based ecosystems, including FastAPI / Node.js APIs for transaction orchestration and synchronization. Machine learning functionality depends on scikit-learn supporting fraud detection, behavioral profiling, clustering, prediction, speech recognition, and voice biometrics across components. Local and centralized data persistence depends on SQLite for on-device offline ledgers, PostgreSQL and MongoDB for backend transaction and user-profile storage.

