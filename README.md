# Projet Machine Learning : Classification de Fleurs Iris

## 1. Objectif
Appliquer plusieurs algorithmes de classification (Arbre de Décision, KNN, Random Forest, AdaBoost...) sur le dataset Iris pour prédire l'espèce d'une fleur à partir de ses mesures physiques.

## 2. Dataset
- Source : UCI Machine Learning Repository (Iris)
- 150 échantillons, 3 classes : *Iris-setosa*, *Iris-versicolor*, *Iris-virginica*
- 4 caractéristiques : `sepal length`, `sepal width`, `petal length`, `petal width`

## 3. Méthodologie
1. Chargement du dataset
2. Analyse exploratoire (EDA) : visualisations avec `seaborn`
3. Prétraitement : séparation Train/Test (80/20) et standardisation (`StandardScaler`)
4. Entraînement et évaluation de **5 modèles** vus en cours
5. Comparaison des performances sur l'ensemble de test

## 4. Résultats

Voici le tableau comparatif des performances obtenues sur le jeu de test :

| Modèle              | Accuracy Test |
| ------------------- | ------------- |
| Random Forest       | 1.0000        |
| KNN (k=5)           | 1.0000        |
| Logistic Regression | 0.9667        |
| Decision Tree       | 0.9333        |
| AdaBoost            | 0.9333        |

 **Le meilleur modèle est Random Forest, avec une accuracy de 100%.**
