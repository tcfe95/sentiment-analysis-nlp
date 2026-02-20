# 🧠 Analyse de Sentiment avec NLP

##  Description du projet

Ce projet consiste à développer un modèle de classification capable de prédire le sentiment d’un texte (positif, négatif ou neutre) à partir de données textuelles.

L’objectif est d’automatiser l’analyse d’avis clients ou de commentaires en utilisant des techniques de Traitement Automatique du Langage Naturel (NLP).

---

##  Technologies utilisées

- Python
- Pandas
- Scikit-learn
- TF-IDF Vectorizer
- Matplotlib / Seaborn

---

##  Pipeline de traitement

1. Nettoyage du texte (suppression ponctuation, caractères spéciaux, stopwords)
2. Tokenisation
3. Vectorisation avec TF-IDF
4. Séparation Train/Test
5. Entraînement et comparaison de plusieurs modèles
6. Évaluation des performances (Accuracy et F1-score)

---

##  Comparaison des modèles

| Modèle | Accuracy | F1-score |
|--------|----------|----------|
| LinearSVC | 0.9567 | 0.6303 |
| Logistic Regression | 0.9517 | 0.5026 |
| Naive Bayes | 0.9509 | 0.4856 |
| Random Forest | **0.9592** | **0.6353** |

---

## 🏆 Meilleur modèle

✅ **Random Forest**  
- Accuracy : 0.9592  
- F1-score : 0.6353  

Ce modèle offre le meilleur compromis entre précision globale et performance sur les classes minoritaires.

---

## 🎯 Interprétation

Bien que l’Accuracy soit élevée pour tous les modèles, l’analyse du F1-score permet une meilleure évaluation des performances sur les classes déséquilibrées.

La comparaison montre que :
- Les modèles linéaires (LinearSVC) sont très performants
- Les modèles d’ensemble (Random Forest) améliorent légèrement la performance globale
- L’évaluation multi-métriques est essentielle en classification

---

## 🚀 Applications possibles

- Analyse d’avis clients (e-commerce)
- Analyse des réseaux sociaux
- Monitoring de réputation
- Analyse automatique de feedback

---

## 🔮 Améliorations futures

- Cross-validation
- Optimisation des hyperparamètres
- Implémentation d’un modèle Deep Learning (LSTM / BERT)
- Déploiement via API ou interface Streamlit
