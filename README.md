🏦 Credit Card Default Prediction
📘 Description
Ce projet applique un modèle de régression logistique pour prédire si un client fera défaut de paiement sur sa carte de crédit au mois suivant. L’analyse repose sur un dataset fourni par l’UCI Machine Learning Repository.

🧾 Dataset utilisé
Nom du fichier : UCI_Credit_Card.csv

Source : UCI Machine Learning Repository

Taille : Environ 30 000 observations

Objectif : Prédire la variable default.payment.next.month (1 = défaut, 0 = pas de défaut)

🧠 Variables principales
LIMIT_BAL : Crédit accordé

SEX, EDUCATION, MARRIAGE, AGE

PAY_0 à PAY_6 : Historique de paiement

BILL_AMT1 à BILL_AMT6 : Montants des factures

PAY_AMT1 à PAY_AMT6 : Montants remboursés

🧼 Prétraitement
Analyse exploratoire (.head(), .describe())

Vérification des classes (dt.SEX.value_counts(), etc.)

Pas encore précisé si des imputations ou normalisations sont appliquées

🤖 Modélisation
Modèle choisi : Régression Logistique

Problème : Classification binaire

Cible : default.payment.next.month

📊 Évaluation des performances
Métriques utilisées :

Accuracy

Matrice de confusion

Classification Report

AUC

F1-Score

🛠️ Outils et bibliothèques
Python

Pandas & NumPy

Matplotlib & Seaborn

Scikit-learn

📁 Fichiers
Project_11.ipynb : Notebook principal

UCI_Credit_Card.csv : Dataset source