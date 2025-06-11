# 🩺 Healthcare ChatBot: Disease Prediction Using Machine Learning

This is a command-line based Healthcare ChatBot that predicts diseases based on user-inputted symptoms using machine learning models. It suggests possible precautions and provides a short description of the diagnosed disease. It uses Decision Trees and Support Vector Machines to make predictions.

---

## 🔍 Features

- Symptom-based disease prediction using **Decision Tree** and **SVM** classifiers
- Reads symptom severity, descriptions, and precautions from CSV files
- Asks interactive symptom-based questions
- Predicts probable diseases based on user inputs
- Offers **secondary prediction** for more accurate diagnosis
- Suggests **precautionary measures**
- Uses **text-to-speech** to read out results (via `pyttsx3`)

---

## 🧠 Algorithms Used

- Decision Tree Classifier (primary prediction)
- Support Vector Machine (model evaluation)
- Label Encoding of output classes
- Feature importance ranking

---

## 📁 Project Structure

```bash
HealthcareChatBot/
│
├── Data/
│   ├── Training.csv
│   └── Testing.csv
│
├── MasterData/
│   ├── symptom_Description.csv
│   ├── symptom_severity.csv
│   └── symptom_precaution.csv
│
├── chatbot.py        # Main Python script
└── README.md         # Project documentation
## 📝 License
This project is licensed under the MIT License – see the [LICENSE](./LICENSE) file for details.
