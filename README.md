# Étude du Réseau Neuronal Convolutif (CNN) pour la Reconnaissance de Chiffres MNIST
Les réseaux neuronaux convolutifs (CNN) sont un type de réseau neuronal particulièrement efficace pour le traitement des données en forme de grille, telles que les images. Dans cette étude, j'ai exploré un CNN pour la reconnaissance de chiffres manuscrits en utilisant le célèbre ensemble de données MNIST. MNIST contient des images de chiffres manuscrits de 28x28 pixels, réparties en 10 classes (de 0 à 9).

# Description
 1. Chargement et Prétraitement des Données : Les données MNIST sont chargées et les étiquettes sont converties en une forme catégorielle.

 2. Construction du Modèle CNN : Un modèle CNN est construit avec des couches de convolution et de pooling pour extraire les caractéristiques des images, suivies de couches denses pour la classification.

 3. Compilation et Entraînement du Modèle : Le modèle est compilé avec l'optimiseur Adam et entraîné sur les données d'entraînement.

 4. Prédictions et Évaluation : Le modèle fait des prédictions sur les données de test, et les résultats sont sauvegardés dans un fichier CSV.

 5. Affichage des Résultats : Une image de l'ensemble de données est affichée avec son étiquette réelle et la prédiction faite par le modèle.
