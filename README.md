# Détection d’Accidents Routiers par Deep Learning
Description du projet

Ce projet a pour objectif de détecter automatiquement les accidents de circulation à partir d’images issues de caméras de surveillance routière en utilisant des techniques de Deep Learning et de vision par ordinateur.

Plusieurs modèles de classification ont été étudiés et comparés :

- CNN classique
- VGG16
- Resnet50
- Système hybride CNN + MobileNetV2

Le modèle hybride a permis d’obtenir les meilleures performances en combinant :

la capacité d’extraction locale des caractéristiques du CNN,
et la puissance du Transfer Learning avec MobileNetV2.

## Objectifs :
 
- Détecter automatiquement les accidents routiers
- Comparer différentes architectures de Deep Learning
- Améliorer les performances grâce au Transfer Learning
- Réduire les erreurs de classification
- Fournir un système intelligent d’aide à la surveillance routière
- 
## Dataset utilisé :

Le dataset utilisé est :
Accident Detection From CCTV Footage

Il contient des images extraites de vidéos de surveillance routière réparties en deux classes :

Accident
Non Accident

Les données ont été prétraitées et augmentées afin d’améliorer la généralisation des modèles.

### Contenu du projet : 
- Notebooks jupyter (.ipynb)
- Modéles entrainés

### Technologies utilisées : 
- Python
- TensorFlow / Keras
- OpenCV
- NumPy
- Matplotlib
- Scikit-learn

 ## Auteurs : 
  - BAAR Khaoula
  - ABDELKAHER Céline
  
