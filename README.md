<img width="687" height="637" alt="ann diabete" src="https://github.com/user-attachments/assets/3f166d95-9c2f-48be-ba03-797e6bc33256" />



# 🏥 ANN Diabetes Prediction API

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)
[![Flask](https://img.shields.io/badge/Framework-Flask-lightgrey.svg)](https://flask.palletsprojects.com/)
[![TensorFlow](https://img.shields.io/badge/ML-TensorFlow-orange.svg)](https://www.tensorflow.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Cette API REST permet de prédire la probabilité de diabète chez un patient en utilisant un réseau de neurones artificiels (**ANN**). Le modèle traite les données biométriques et renvoie un résultat instantané.

---

## 🛠️ Stack Technique

* **Langage :** Python 3.x
* **Framework Web :** Flask
* **Deep Learning :** TensorFlow / Keras
* **Traitement de données :** NumPy
* **Format de données :** JSON

## 📂 Structure des fichiers

* `app.py` : Le serveur Flask et la logique d'inférence.
* `model/model_pima_ann.h5` : Le modèle entraîné (format Keras).
* `model/scaler_meta.json` : Paramètres de normalisation (moyenne et écart-type) pour assurer la précision des prédictions.

## 🚀 Installation Rapide

1. **Cloner le dépôt :**
   ```bash
   git clone [https://github.com/cherif808/ann-diabetes-api.git](https://github.com/cherif808/ann-diabetes-api.git)
   cd ann-diabetes-api
