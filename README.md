# MNIST_FASHION

# Projet MNIST Fashion - Modèle de Deep Learning

Bienvenue dans le projet MNIST Fashion! Ce projet utilise le jeu de données MNIST Fashion pour entraîner et évaluer des modèles de deep learning pour la classification d'images. MNIST Fashion est une alternative au jeu de données MNIST classique, où les chiffres manuscrits sont remplacés par des images de vêtements.

## Table des matières

1. [Aperçu du projet](#aperçu-du-projet)
2. [Installation](#installation)
3. [Utilisation](#utilisation)
4. [Contribuer](#contribuer)
5. [Licence](#licence)
6. [Références](#références)

## Aperçu du projet

Ce projet vise à explorer différentes architectures de réseaux de neurones pour la classification d'images en utilisant le jeu de données MNIST Fashion. Il comprend des exemples de modèles de deep learning utilisant des réseaux de neurones convolutifs (CNN), des techniques d'optimisation, et des méthodes de régularisation avancées.

## Installation

1. Clonez ce dépôt:
    ```bash
    git clone https://github.com/votre-utilisateur/mnist-fashion.git
    cd mnist-fashion
    ```

2. Créez un environnement virtuel et activez-le:
    ```bash
    python -m venv env
    source env/bin/activate  # Sur Windows, utilisez `env\Scripts\activate`
    ```

3. Installez les dépendances:
    ```bash
    pip install -r requirements.txt
    ```

## Utilisation

1. Téléchargez le jeu de données MNIST Fashion:
    ```python
    from tensorflow.keras.datasets import fashion_mnist
    (x_train, y_train), (x_test, y_test) = fashion_mnist.load_data()
    ```

2. Exécutez le notebook pour entraîner et évaluer le modèle:
    ```bash
    jupyter notebook mnist_fashion.ipynb
    ```

## Contribuer

Les contributions sont les bienvenues! Veuillez suivre les étapes ci-dessous pour contribuer à ce projet:

1. Fork ce dépôt.
2. Créez une branche pour votre fonctionnalité (`git checkout -b feature-nouvelle-fonctionnalité`).
3. Commitez vos changements (`git commit -am 'Ajoute une nouvelle fonctionnalité'`).
4. Poussez votre branche (`git push origin feature-nouvelle-fonctionnalité`).
5. Ouvrez une Pull Request.

## Licence

Ce projet est sous licence MIT. Voir le fichier `LICENSE` pour plus d'informations.

## Références

- [Keras Documentation](https://keras.io/)
- [MNIST Fashion Dataset](https://github.com/zalandoresearch/fashion-mnist)

Merci d'avoir consulté ce projet! Si vous avez des questions ou des suggestions, n'hésitez pas à ouvrir une issue ou à me contacter.


Brief:

# Mini-projet MNIST FASHION

### Brief de Projet: Entraînement d'un Modèle sur le Dataset Fashion MNIST avec Keras

**Objectif:**
Entraîner un modèle de deep learning sur le jeu de données Fashion MNIST, disponible via Keras, pour classifier des images de vêtements.

**Durée du projet:**
Demi-journée à une journée complète.

**Tâches Principales:**

1. **Chargement des Données**
    - Récupérez le dataset Fashion MNIST en utilisant `keras.datasets`.
2. **Construction du Modèle**
    - Utilisez l'API séquentielle de Keras pour construire votre modèle.
    - Définissez librement le nombre de couches, le nombre d'unités par couche, et les fonctions d'activation.
    - Configurez la couche de sortie et choisissez la fonction de coût appropriée à la tâche de classification.
3. **Implémentation de l'Early Stopping**
    - Mettez en place l'early stopping pour arrêter l'entraînement lorsque l'accuracy sur le set de validation ne s'améliore plus.
4. **Intégration de TensorBoard**
    - Configurez TensorBoard pour le suivi de l'entraînement et de la validation du modèle.
5. **Baseline avec Régression Logistique**
    - Avant de commencer avec les modèles de deep learning, établissez un score baseline avec un modèle de régression logistique.

**Métriques d'Évaluation:**

- Utilisez l'accuracy comme principal indicateur de performance.

**Consignes Supplémentaires:**

- Assurez-vous de bien documenter vos expériences et configurations.
- Comparez les performances de différentes architectures et configurations pour déterminer la plus efficace.
- Présentez vos résultats et conclusions de manière claire et structurée.

**Ressources Nécessaires:**

- Environnement de développement Python avec accès à TensorFlow/Keras.
- Accès à des ressources computationnelles suffisantes pour l'entraînement des modèles.

Ce brief est conçu pour vous guider à travers les étapes essentielles de l'entraînement d'un modèle de deep learning, depuis la préparation des données jusqu'à l'évaluation et l'amélioration des performances, tout en intégrant des outils de suivi et de régulation pour optimiser les résultats.
