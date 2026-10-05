# ArtificialInquiries_EXE_NUM-6
# Ex6 – Concevoir votre test d'IA

## 1. Présentation de l'exercice

L'exercice **« Design Your AI Test »** a pour objectif d'évaluer les capacités et les limites des modèles de langage de grande taille (**LLM – Large Language Models**) dans la réalisation de tâches liées aux pratiques professionnelles.

L'objectif principal est d'identifier quatre tâches professionnelles essentielles, puis de les utiliser pour concevoir un test permettant d'évaluer concrètement ce qu'une IA est capable de réaliser dans un contexte professionnel.

L'exercice est organisé en trois parties :

- **Partie 1 – Classification des tâches :** identifier et organiser les différentes tâches professionnelles selon deux critères : les tâches que l'on doit réaliser et celles que l'on apprécie réaliser.
- **Partie 2 – Sélection des tâches principales :** choisir quatre tâches représentatives de la diversité et de l'importance du travail réalisé.
- **Partie 3 – Réflexion critique :** analyser les tâches sélectionnées, déterminer ce que l'IA peut apporter et identifier les limites et les risques liés à leur délégation à une IA.

---

## 2. Objectifs

Les principaux objectifs de cet exercice sont :

- Identifier les tâches importantes dans une activité professionnelle.
- Distinguer les tâches obligatoires des tâches que l'on apprécie.
- Sélectionner quatre tâches représentatives de son activité.
- Concevoir des tests permettant d'évaluer les capacités d'une IA.
- Évaluer la qualité et la pertinence des solutions générées par une IA.
- Identifier les tâches pouvant être assistées ou automatisées par une IA.
- Identifier les tâches nécessitant une expertise et une validation humaine.

---

## 3. Les quatre tâches principales sélectionnées

Dans le cadre d'un profil orienté vers **l'Intelligence Artificielle et les Systèmes d'Information**, quatre tâches principales ont été sélectionnées.

### Tâche 1 – Analyse et prétraitement des données

#### Description

Analyser, nettoyer, transformer et préparer des jeux de données destinés à des applications d'intelligence artificielle et d'apprentissage automatique.

#### Activités principales

- Comprendre la structure et le contenu d'un jeu de données.
- Identifier les valeurs manquantes et les incohérences.
- Supprimer ou traiter les données problématiques.
- Encoder les variables catégorielles.
- Normaliser ou standardiser les données.
- Détecter les problèmes de fuite de données (*data leakage*).
- Sélectionner les variables pertinentes.
- Préparer les données pour l'entraînement d'un modèle.

#### Objectif du test avec une IA

Évaluer si une IA est capable d'analyser un jeu de données, de proposer des méthodes de prétraitement adaptées, de générer du code Python correct et d'expliquer les choix effectués.

---

### Tâche 2 – Développement et évaluation de modèles d'IA

#### Description

Développer, entraîner et évaluer des modèles d'apprentissage automatique afin de résoudre un problème de classification ou de prédiction.

#### Activités principales

- Identifier l'algorithme adapté au problème.
- Préparer les données d'entraînement et de test.
- Entraîner différents modèles.
- Régler les hyperparamètres.
- Évaluer les performances des modèles.
- Comparer plusieurs algorithmes.
- Interpréter les résultats.
- Identifier les limites du modèle.

#### Objectif du test avec une IA

Évaluer la capacité d'une IA à choisir des algorithmes adaptés, générer un pipeline d'entraînement fonctionnel, interpréter les métriques et proposer des améliorations pertinentes.

---

### Tâche 3 – Développement d'applications et d'API

#### Description

Concevoir et développer des applications ou des API REST permettant d'intégrer des modèles d'intelligence artificielle dans des systèmes fonctionnels.

#### Activités principales

- Développer le backend d'une application.
- Créer des API REST avec FastAPI.
- Intégrer un modèle d'intelligence artificielle.
- Assurer la communication entre les différents composants.
- Gérer les données et les requêtes.
- Conteneuriser l'application avec Docker.
- Tester et déboguer l'application.
- Documenter les fonctionnalités développées.

#### Objectif du test avec une IA

Évaluer la capacité d'une IA à produire du code fonctionnel, intégrer un modèle d'IA dans une API, identifier des erreurs et proposer une solution logicielle maintenable.

---

### Tâche 4 – Conception de l'architecture d'un système d'information

#### Description

Concevoir l'architecture d'un système d'information en définissant ses composants, leurs interactions et les technologies nécessaires.

#### Activités principales

- Identifier les besoins fonctionnels et techniques.
- Définir les différents composants du système.
- Choisir les technologies appropriées.
- Définir les interactions entre les composants.
- Concevoir l'architecture backend et frontend.
- Prendre en compte la sécurité.
- Prendre en compte la scalabilité.
- Prendre en compte la maintenabilité.
- Réaliser des diagrammes d'architecture.

#### Objectif du test avec une IA

Évaluer si une IA est capable de proposer une architecture cohérente, de justifier ses choix technologiques, d'identifier les problèmes potentiels et d'adapter son architecture aux contraintes du projet.

---

# 4. Solutions techniques pour réaliser l'exercice

Plusieurs technologies peuvent être utilisées afin de réaliser et tester les différentes tâches.

| Composant | Technologie | Utilisation |
|---|---|---|
| Assistant IA | ChatGPT / autre LLM | Génération et analyse des solutions |
| Langage | Python | Implémentation et expérimentation |
| Analyse de données | Pandas, NumPy | Nettoyage et analyse des données |
| Machine Learning | Scikit-learn, XGBoost | Entraînement des modèles |
| API | FastAPI | Création d'API REST |
| Conteneurisation | Docker | Déploiement et isolation |
| Diagrammes | Mermaid | Représentation des architectures |
| Gestion de versions | Git / GitHub | Gestion du projet |
| Documentation | Markdown | Documentation de l'exercice |

---

## 5. Méthodologie de test

Afin d'obtenir une évaluation pertinente, chaque tâche sera testée selon une méthodologie commune.

### Étape 1 – Définition de la tâche

Définir précisément le problème à résoudre, les données disponibles, les contraintes techniques et le résultat attendu.

### Étape 2 – Création du prompt

Préparer une consigne claire destinée au modèle d'IA.

Le même contexte et les mêmes contraintes doivent être utilisés afin de pouvoir comparer les résultats.

### Étape 3 – Génération de la solution

Soumettre la tâche à l'IA et récupérer :

- le raisonnement ou les explications fournies ;
- le code généré ;
- les choix techniques proposés ;
- les résultats attendus.

### Étape 4 – Implémentation

Exécuter et tester concrètement la solution proposée par l'IA.

Pour le code Python, par exemple :

```text
Python
   ↓
Exécution du code
   ↓
Résultats
   ↓
Validation
