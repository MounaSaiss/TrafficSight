# 🚘 Vehicle Detection System with YOLOv9

## 📌 Aperçu du Projet
Ce projet met en œuvre un pipeline complet de vision par ordinateur orienté vers la **détection et la localisation d'objets (véhicules)** dans des images en utilisant l'architecture de pointe **YOLOv9**. 

L'objectif principal est de maîtriser l'ensemble du workflow de Deep Learning : de l'exploration des données à l'analyse critique des performances du modèle sur GPU.

---

## 🎯 Objectifs & Fonctionnalités

- **Préparation & Vérification du Dataset :** Audit de la qualité des images et des annotations de plusieurs catégories de véhicules.
- **Création du Jeu de Test :** Structuration propre des jeux d'entraînement, de validation et de test.
- **Fine-Tuning avec YOLOv9 :** Utilisation d'un modèle préentraîné pour adapter les poids aux spécificités du jeu de données.
- **Entraînement sur GPU :** Optimisation des hyperparamètres pour accélérer la convergence.
- **Évaluation des Performances :** Analyse approfondie via les métriques standard (mAP@0.5, mAP@0.5:0.95, Precision, Recall, Matrice de confusion).
- **Analyse des Prédictions :** Visualisation des boîtes englobantes (*bounding boxes*) et analyse des erreurs de détection.

---

## 🛠️ Technologies & Outils

- **Architecture :** YOLOv9 (PyTorch / Ultralytics)
- **Langage :** Python 3.x
- **Librairies :** OpenCV, NumPy, Matplotlib, Pandas, PyTorch
- **Environnement :** Entraînement sur GPU (Google Colab / Kaggle / CUDA local)
