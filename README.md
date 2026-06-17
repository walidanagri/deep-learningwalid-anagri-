# 🎓 Projet de Fin de Module — Deep Learning

## EMSI Casablanca — École Marocaine des Sciences de l'Ingénieur

### Département Informatique — Année universitaire 2025–2026

**Étudiant :** ANAGRI Walid
**Module :** Deep Learning
**Intitulé :** Conception, implémentation, comparaison et analyse de modèles de Deep Learning pour données tabulaires, images et séquences

---

## 📝 Description du projet

Ce projet propose une étude approfondie des principales architectures de Deep Learning à travers leur conception, leur implémentation et leur évaluation à l'aide du framework **PyTorch**. L'objectif est de comprendre comment chaque architecture s'adapte à la nature des données traitées et d'analyser les performances obtenues selon différents contextes d'apprentissage.

Le travail est structuré en trois grandes parties complémentaires :

* **Partie I — Réseaux de Neurones Multicouches (MLP) :** étude de la classification supervisée sur le dataset **Breast Cancer Wisconsin**. Cette partie comprend le prétraitement des données, la construction de plusieurs architectures MLP, la comparaison de différentes méthodes d'initialisation des poids (Gaussienne, Constante et Xavier) ainsi que l'analyse des performances obtenues à travers plusieurs métriques d'évaluation. *(Accuracy obtenue : ≈ 97 %).*

* **Partie II — Réseaux de Neurones Convolutifs (CNN) :** application des techniques de vision par ordinateur au dataset **Fashion-MNIST**. Cette section inclut le développement d'un modèle convolutionnel inspiré de LeNet, l'étude de l'impact de différents paramètres architecturaux ainsi que la visualisation des représentations apprises par le réseau grâce aux cartes de caractéristiques (Feature Maps). *(Accuracy obtenue : ≈ 91 %).*

* **Partie III — Réseaux Récurrents (RNN, LSTM, GRU) et Architecture Seq2Seq :** exploration des modèles dédiés au traitement des séquences textuelles. Cette partie met en évidence les problématiques liées à la disparition et à l'explosion des gradients, compare les performances des architectures récurrentes modernes et implémente un modèle Encodeur–Décodeur utilisant le Teacher Forcing, le Greedy Search et le Beam Search pour la génération de séquences.

---

## 🛠️ Prérequis et Dépendances

Le projet est développé sous **Python 3.10+** et utilise principalement les bibliothèques suivantes :

* PyTorch
* TorchVision
* Scikit-Learn
* Pandas
* NumPy
* Matplotlib
* Seaborn
* NLTK

L'utilisation d'un GPU est recommandée afin d'accélérer les phases d'entraînement des modèles.

---

## 🚀 Exécution du projet

### Option 1 : Google Colab (Recommandée)

1. Importer le fichier **Projet_DeepLearning_Walid_ANAGRI.ipynb** dans Google Drive.
2. Ouvrir le notebook avec **Google Colaboratory**.
3. Activer l'accélération matérielle GPU :

   * Exécution
   * Modifier le type d'exécution
   * Sélectionner **GPU**
4. Exécuter les cellules dans l'ordre afin de reproduire l'ensemble des expériences et résultats présentés dans le rapport.

Les bibliothèques nécessaires seront installées automatiquement au démarrage du notebook.
