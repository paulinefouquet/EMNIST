# Modele de reconnaissance: MNIST et EMNIST

## 1_mnist
Entrainement d'un modèle sur la reconnaissance de chiffre
mnist : accuracy: 0.9763 en 10s

## 2-emnist
Entrainement d'un modèle sur la reconnaissance de chiffre
emnist : accuracy: 0.9282 en 67s

## 3_reconnaisance_letter
Traitement d'image webcam ou drawing de lettre
Prediction grâce au modele entrainé sur le emnist

Le modèle entrainé sur le EMNIST reconnait les drawings lettres à conditions de les générer avec un trait assez épais: context.lineWidth = 15; testé sur 3 images : 100%