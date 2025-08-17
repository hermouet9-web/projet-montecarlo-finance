# Simulation et Analyse Financière en Python

Ce projet a pour objectif de manipuler des données financières réelles et de simuler des trajectoires de prix en utilisant un mouvement brownien géométrique (GBM).
Il combine une approche pratique (Python, programmation orientée objet) et une approche théorique (finance quantitative).

---

## Fonctionnalités

* Téléchargement automatique des données de marché via yfinance
* Visualisation des prix de clôture et des log-returns
* Estimation des paramètres financiers :

  * \$\mu\$ (rendement espéré)
  * \$\sigma\$ (volatilité)
* Simulation Monte Carlo de trajectoires de prix avec un modèle GBM
* Code organisé en classes Python (POO) pour plus de clarté et de réutilisabilité

---

## Installation

1. Cloner le repository

```bash
git clone https://github.com/tonpseudo/ton-repo.git
cd ton-repo
```

2. Créer un environnement virtuel (optionnel mais recommandé)

```bash
python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate     # Windows
```

3. Installer les dépendances

```bash
pip install -r requirements.txt
```


## Technologies utilisées

* Python 3.x
* `yfinance`
* `numpy`
* `pandas`
* `matplotlib`

