# AHAKKOUN Houssam
<img src="sb3.jpg" style="height:464px;margin-right:432px"/>


# Compte Rendu du Notebook *Ahakkoun_Houssam.ipynb*

Le notebook *Ahakkoun_Houssam.ipynb* présente une étude complète d'un
graphe social en utilisant la bibliothèque **PyTorch Geometric**,
combinée à **NetworkX** pour la visualisation et à des modèles de
**Graph Neural Networks (GNN)** pour l'analyse prédictive.

## 1. Chargement des données et préparation

Deux jeux de données sont utilisés : - **Karate Club Graph** - **Davis
Southern Women Network**

Les caractéristiques du graphe sont analysées : nombre de nœuds, arêtes,
features et labels.

## 2. Visualisation du graphe

Une visualisation est générée permettant d'observer la structure du
réseau et les connexions entre les nœuds.

## 3. Analyse structurelle du réseau

Des métriques importantes sont calculées : - centralité - coefficient de
clustering - densité - distribution des degrés

## 4. Modélisation par Graph Neural Network (GCN)

Un modèle **GCN** est construit avec deux couches de convolution pour
réaliser une **classification des nœuds**.

## 5. Entraînement du modèle

Le modèle est entraîné avec CrossEntropyLoss et Adam. La précision et la
perte sont suivies au cours des époques.

## 6. Évaluation des performances

L'évaluation inclut : - accuracy - rapport de classification - matrice
de confusion - visualisation des labels vrais vs prédits

## 7. Prédiction de liens (Link Prediction)

Un second modèle est utilisé pour prédire les liens manquants dans le
graphe grâce à un mécanisme encodeur--décodage basé sur un GCN.

## Conclusion

Le notebook montre une maîtrise claire de l'analyse de graphes, des GNN
et de PyTorch Geometric, couvrant analyse exploratoire, modélisation et
prédiction avancée.
