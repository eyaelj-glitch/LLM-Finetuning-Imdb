# Fine-tuning de DistilBERT sur IMDB

Projet Large Language Models, 3LIG, 2026/2027.

**Objectif** : classer des avis de films en positif ou négatif.

**Contenu**
- `projet_llm_finetuning_final.ipynb` : notebook Colab (moins de 15 minutes sur GPU T4)
- `requirements.txt` : bibliothèques utilisées

**Résultats (test, 500 avis)** : baseline TF-IDF + LogReg 0.806 d'accuracy, DistilBERT fine-tuné 0.832.

**Comment l'utiliser**
1. Ouvrir le notebook dans Google Colab.
2. Exécution > Modifier le type d'exécution > T4 GPU.
3. Exécution > Tout exécuter.
