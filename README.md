# 🌱 LunuNeth AI - Onion Crop Health Monitoring & Diagnostic System

LunuNeth AI is an intelligent, multi-platform crop health advisory system tailored for Sri Lankan onion farmers. It empowers farmers through an interactive ecosystem that combines Computer Vision and an Active Learning-Enhanced Conversational Diagnostic Chatbot to identify diseases, pests, and nutrient deficiencies.

---

## ✨ Features

- **📱 Mobile App (Flutter)**: A cross-platform, user-friendly mobile application designed for farmers to easily photograph their crops and interact with the diagnostic chatbot.
- **💬 Conversational Differential Diagnosis**: Multi-turn dialogue system that asks intelligent follow-up questions to pinpoint crop health problems using Bayesian Belief Networks.
- **🌍 Multi-Language Support**: Full support for English, Sinhala, and Singlish text handling to serve local farming communities natively.
- **👁️ Computer Vision Integration**: Automated imagery analysis to detect Purple Blotch, common pests, and nutrient deficiencies.
- **🧠 Active Learning Loop**: The system collects farmer feedback to continuously retrain and improve NLP models over time.

---


## 🏗️ Architecture

1. **Farmer Input**: The farmer inputs symptoms via text or image in the Flutter mobile app.
2. **Backend Processing**: The app sends the data to the Python FastAPI backend.
3. **NLP Pipeline**: Detects language, classifies intent, and extracts agricultural entities (symptoms, diseases).
4. **Bayesian Diagnosis Engine**: Uses a Bayesian Belief Network (BBN) to compute probabilities and uses Information Gain to select the best follow-up question.
5. **Response Delivery**: The generated diagnosis or targeted follow-up question is sent back to the Flutter app natively.

---

## 🤝 Contributing
Contributions, issues, and feature requests are welcome! Feel free to check the issues page or submit a pull request.
