# Credit-project
This is a demo project to elaborate how Machine Learn Models are deployed on production using Flask API
Ce code Python a pour but principal de créer un modèle de machine learning supervisé pour prédire si un prêt sera accordé ou non, à partir d’un jeu de données (train.csv) contenant des informations sur les emprunteurs.
# Prerequisites
You must have Scikit Learn, Pandas (for Machine Leraning Model) and Flask (for API) installed.
#Objectif global
1. Nettoyer et préparer les données (Loan_ID, valeurs manquantes, encodage des catégories...),
2. Analyser les données (exploration visuelle avec seaborn, calcul de proportions),
3. Entraîner différents modèles de classification (régression logistique, KNN, arbre de décision),
4. Évaluer leur précision,
5. Sauvegarder le meilleur modèle avec pickle pour une utilisation future.
# Project Structure
This project has four major parts :

1. model.py - This contains code fot our Machine Learning model to predict employee salaries absed on trainign data in 'hiring.csv' file.
2. app.py - This contains Flask APIs that receives employee details through GUI or API calls, computes the precited value based on our model and returns it.
3. request.py - This uses requests module to call APIs already defined in app.py and dispalys the returned value.
4. templates - This folder contains the HTML template to allow user to enter employee detail and displays the predicted employee salary.
