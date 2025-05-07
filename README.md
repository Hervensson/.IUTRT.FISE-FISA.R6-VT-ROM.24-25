# Projet de Classification des Tumeurs Cérébrales à partir d'IRM

## Description
Ce projet développe un modèle de classification des tumeurs cérébrales à partir d'images d'IRM, utilisant **EfficientNetB0** pré-entraîné pour classer les tumeurs en quatre catégories : gliome, méningiome, tumeur hypophysaire, et absence de tumeur.

## Objectif
Fournir une solution d'IA pour aider les radiologues à identifier rapidement les types de tumeurs cérébrales à partir d'IRM.

## Étapes

1. **Prétraitement** : Téléchargement des données, redimensionnement des images à 224x224px, et normalisation des pixels.
2. **Entraînement** : Utilisation du modèle **EfficientNetB0** pour entraîner la classification des tumeurs.
3. **Prédiction** : Le modèle prédit la classe des tumeurs pour des images d'IRM inconnues.

## Prérequis
- Python 3.x
- TensorFlow, Keras
- Matplotlib, NumPy, Seaborn
- Kaggle pour télécharger les données

## Installation

1. Clonez ce dépôt :

   ```bash
   git clone https://github.com/votre-utilisateur/votre-depot.git
   
2. Installez les dépendances :
 ```bash
  pip install -r requirements.txt
  ````
3. Téléchargez les données IRM de Kaggle :
 ```bash
  import kaggle
kaggle.api.dataset_download_files('sartajbhuvaji/brain-tumor-classification-mri', path='data/', unzip=True)
````
Résultats
Le modèle permet de classer les tumeurs avec une certaine précision, mais il montre des signes de sur-apprentissage, indiquant un besoin d'amélioration de la généralisation.

Conclusion
Ce projet est une base solide pour la classification des tumeurs cérébrales. Des améliorations sont possibles pour améliorer la précision et la généralisation du modèle.


### Explications :
- **Description** et **Objectif** sont résumés pour présenter brièvement le projet.
- **Étapes** est une version condensée des processus du projet.
- **Prérequis** et **Installation** détaillent de manière concise les étapes nécessaires.
- **Résultats** et **Conclusion** mettent en avant les performances du modèle tout en suggérant des améliorations possibles.

