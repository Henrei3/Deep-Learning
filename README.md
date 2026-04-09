# Fouille de Réseaux et d'Information (FRI) - Travaux Pratiques

Ce dépôt contient l'ensemble des travaux pratiques réalisés dans le cadre du module **FRI** du Master IAFA. Ces travaux couvrent les fondamentaux de la Recherche d'Information (RI), l'analyse de graphes et les systèmes d'IA générative basés sur la récupération de documents.

## 🚀 Thématiques abordées
Ce cursus suit l'évolution des moteurs de recherche : des modèles vectoriels classiques aux systèmes de **RAG (Retrieval Augmented Generation)**.

## 📂 Structure du dépôt

### TP 1 : Fondamentaux de la Recherche d'Information
* **Objectif :** Implémenter les briques de base d'un moteur de recherche.
* **Concepts clés :** * Prétraitement de texte (tokenisation, stop-words, stemming).
    * Construction d'un **index inversé**.
    * Modèle booléen vs Modèle vectoriel.

### TP 2 : Modèle Vectoriel et Pondération TF-IDF
* **Objectif :** Classer les documents par pertinence par rapport à une requête.
* **Concepts clés :** * Calcul des scores **TF-IDF** (Term Frequency - Inverse Document Frequency).
    * Mesure de similarité (similarité cosinus).
    * Évaluation des performances (Précision, Rappel, F-score).

### TP 3 : Analyse de Graphes et PageRank
* **Objectif :** Comprendre l'importance de la structure des liens dans le Web.
* **Concepts clés :** * Représentation de réseaux sous forme de graphes.
    * Implémentation de l'algorithme **PageRank**.
    * Analyse de centralité et influence des nœuds.

### TP 4 : Recherche d'Information Sémantique
* **Objectif :** Dépasser la simple correspondance de mots-clés.
* **Concepts clés :** * Introduction aux **Embeddings** (représentations vectorielles denses).
    * Utilisation de vecteurs de mots pour la recherche par similarité sémantique.

### TP 5 : LLM, LangChain et RAG (Retrieval Augmented Generation)
* **Objectif :** Créer un système de Question-Réponse intelligent sur des documents privés.
* **Concepts clés :** * Utilisation du framework **LangChain**.
    * Orchestration de Large Language Models (LLM).
    * Mise en place d'un pipeline **RAG** : Vector Store (ChromaDB/FAISS), indexation de PDF et génération de réponses augmentée par la recherche.

## 🛠️ Stack Technique
* **Langage :** Python 3.10+
* **Frameworks IA :** [LangChain](https://www.langchain.com/), OpenAI API / Hugging Face.
* **Traitement de texte :** NLTK, Scikit-learn.
* **Graphes :** NetworkX.
* **Stockage Vectoriel :** ChromaDB / FAISS.

## ⚙️ Installation & Usage

1. **Installation des dépendances :**
   ```bash
   pip install langchain openai chromadb sentence-transformers networkx scikit-learn
