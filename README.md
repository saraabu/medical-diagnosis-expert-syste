# medical-diagnosis-expert-syste
A rule-based expert system for medical diagnosis using CLIPS and Python
# 🩺 Medical Diagnosis Expert System

A symbolic AI system that simulates medical diagnosis using CLIPS rule-based reasoning and Python-based data handling.

---

## 🧠 Overview

This project is a medical expert system that takes in patient symptoms and returns likely diagnoses along with recommended precautions. It combines structured medical datasets, rule-based knowledge representation, and a simple prototype user interface.

---

## 📁 Project Structure

| File | Description |
|------|-------------|
| `DatasetUnderstanding.ipynb` | Exploratory data analysis of symptoms and diagnoses |
| `KnowledgeEngineering.ipynb` | Design of expert rules and symptom modeling |
| `UserInterfaceDevelopment.ipynb` | Prototype interface for interacting with the expert system |
| `medical_rules.clp` | CLIPS-based symbolic rules for diagnosis |
| `dataset.csv` | Primary training/diagnostic dataset |
| `symptom_Description.csv` | Human-readable symptom details |
| `symptom_precaution.csv` | Suggested precautions per condition |
| `Symptom-severity.csv` | Severity scale for each symptom |

---

## ⚙️ Tools & Technologies

- **CLIPS**: Rule-based expert system engine
- **Python + Jupyter Notebook**
- **Pandas** for data manipulation
- **CSV files** as data sources

---

## 🎯 Features

- Rule-based diagnosis from symptom inputs
- Severity-weighted symptom processing
- Precaution recommendations
- Clean interface prototype
- Dataset-driven rule creation

---

## ✍️ My Role

I designed the rule base in CLIPS, developed the data processing pipeline in Python, and built a simple UI prototype to demonstrate the interaction between symptoms and medical logic.

---

## 📈 Sample Use Case

> **Input:** ['fatigue', 'high_fever', 'cough']  
> **Output:** Likely condition: *Typhoid*  
> **Recommended precautions:** Stay hydrated, rest, consult a physician.

---

## 🔗 Future Enhancements

- Add real-time UI for diagnosis
- Convert CLIPS rules to Python-native logic
- Connect to external health APIs

---

## 🧑‍💻 Author

**Sara A.**  
Recent Computer Science graduate specializing in Data Science & Big Data  
GitHub: [@saraabu](https://github.com/saraabu)

