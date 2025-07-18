```markdown
# 🏘️ Prédiction de Prix Immobiliers au Maroc

Ce projet vise à prédire le prix des biens immobiliers au Maroc en utilisant des algorithmes de Machine Learning à partir d'un jeu de données contenant diverses caractéristiques des biens.

## 📁 Structure des fichiers

```

├── data/
│   ├── cleaned\_data.csv
│   └── raw\_data.csv
├── notebooks/
│   ├── 1\_EDA.ipynb
│   ├── 2\_Preprocessing.ipynb
│   └── 3\_Modeling.ipynb
├── models/
│   ├── random\_forest\_model.pkl
│   └── gradient\_boosting\_model.pkl
├── utils/
│   └── preprocessing.py
├── report/
│   └── rapport\_projet.pdf
├── main.py
└── README.md

````

## ⚙️ Instructions d’exécution

1. **Cloner le projet** :
```bash
git clone https://github.com/votre-utilisateur/projet-immo-maroc.git
cd projet-immo-maroc
````

2. **Créer un environnement virtuel** :

```bash
python -m venv env
source env/bin/activate  # Windows : env\Scripts\activate
```

3. **Installer les dépendances** :

```bash
pip install -r requirements.txt
```

4. **Lancer le script principal** :

```bash
python main.py
```

## 🔍 Modèles inclus

* Régression Linéaire
* Forêt Aléatoire
* Gradient Boosting
* SVR

## 📊 Résultats

Les meilleurs résultats ont été obtenus avec le modèle Random Forest avec un R² de 0.18 sur les données de test.

## 👨‍💻 Auteur

Souad Benlahcen – [LinkedIn](https://www.linkedin.com/in/souad-benlahcen)

