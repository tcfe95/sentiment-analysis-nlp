# 🧠 Analyse de Sentiment Twitter (NLP)

##  Description du projet
Ce projet consiste à analyser automatiquement le sentiment des tweets (positif, négatif, neutre) en utilisant des techniques de Traitement Automatique du Langage Naturel (NLP) et du Machine Learning.

Le dataset utilisé provient de Twitter et contient des tweets annotés avec leur polarité.

---

##  Technologies utilisées
- Python
- Pandas, NumPy
- Scikit-learn
- NLTK
- Matplotlib / Seaborn

---

##  Pipeline de traitement
1. Nettoyage du texte : suppression ponctuation, stopwords, caractères spéciaux  
2. Tokenisation et vectorisation avec TF-IDF  
3. Séparation Train/Test  
4. Entraînement et comparaison de plusieurs modèles :  
   - LinearSVC  
   - Logistic Regression  
   - Naive Bayes  
   - Random Forest  
5. Évaluation des performances avec **Accuracy** et **F1-score**  

---

## 📊 Résultats / Évaluation des modèles

| Modèle | Accuracy | F1-score |
|--------|----------|----------|
| LinearSVC | 0.9567 | 0.6303 |
| Logistic Regression | 0.9517 | 0.5026 |
| Naive Bayes | 0.9509 | 0.4856 |
| Random Forest | **0.9592** | **0.6353** |

✅ Meilleur modèle : **Random Forest**  
- Accuracy = 0.9592  
- F1-score = 0.6353  

---

##  Description détaillée
L’objectif est de classifier les tweets selon leur polarité et de démontrer l’efficacité de différents modèles de classification.  
Le Random Forest obtient le meilleur compromis entre précision globale et performance sur les classes minoritaires.

Ce projet montre :
- La capacité à traiter et vectoriser du texte brut  
- L’importance de la comparaison de modèles  
- L’application pratique du NLP dans des problématiques réelles (analyse de feedback, monitoring des réseaux sociaux)

---

##  Perspectives d’amélioration
- Optimisation des hyperparamètres et Cross-Validation  
- Utilisation de modèles Deep Learning (LSTM / BERT)  
- Déploiement du modèle via API ou interface Streamlit  

---

## 🔗 Lien pour ouvrir dans Colab
[Ouvrir le notebook dans Colab](https://colab.research.google.com/github/ton-username/sentiment-analysis-nlp/blob/main/Analyse_Sentiment_NLP.ipynb)


## 📊 Dataset

Le dataset utilisé pour ce projet est disponible publiquement :  
[Twitter Sentiment Analysis Dataset](https://raw.githubusercontent.com/dD2405/Twitter_Sentiment_Analysis/master/train.csv)

Il contient des tweets annotés avec leur polarité pour l’analyse de sentiment.
