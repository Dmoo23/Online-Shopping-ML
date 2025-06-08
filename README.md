# 🔍 Betrugserkennung bei Bestellungen mit Machine Learning

## 🧠 Projektübersicht

In diesem Projekt wurde ein Machine-Learning-Modell entwickelt, um vorherzusagen, ob eine Bestellung **betrügerisch** ist oder nicht. Ziel war es, anhand historischer Transaktionsdaten ein zuverlässiges Klassifikationsmodell zu erstellen, das potenziellen **Online-Betrug** frühzeitig erkennen kann.

Zur Umsetzung kam das leistungsstarke **XGBoost-Modell** zum Einsatz – ein Gradient-Boosting-Algorithmus, der sich besonders gut für Klassifikationsaufgaben mit strukturierten Daten eignet.

---

## 🛠️ Technologien & Tools

- **Programmiersprache**: Python 3
- **Machine-Learning-Framework**: XGBoost
- **Weitere Bibliotheken**:
  - `pandas` – Datenvorverarbeitung
  - `scikit-learn` – Modelltraining, Metriken, Preprocessing
  - `numpy` – numerische Berechnungen

---

## 🔎 Projektschritte

Das Projekt umfasste folgende Kernschritte:

1. **Datenbereinigung & Feature Engineering**  
   - Entfernen unvollständiger oder irrelevanter Daten  
   - Erstellung neuer Merkmale auf Basis vorhandener Informationen

2. **Modellierung mit XGBoost**  
   - Training des Klassifikationsmodells  
   - Hyperparameter-Tuning mit GridSearchCV  
   - Evaluierung anhand von Accuracy, Precision, Recall und F1-Score

3. **Modellbewertung**  
   - Das Modell wurde durch den ROC Score bewertet
