# Analyse du Dataset - Netflix

## Page web de l'application

Pour accéder directement à l'application sans devoir exécuter le code, se rendre à l'adresse suivante:

`https://projet-netflix-data-analysis.streamlit.app/`

## Accès depuis VS Code

### Prérequis

- Avoir Python installé (version **3.10 ou plus**).
- Avoir le fichier **`data/netflix_titles.csv`** dans un dossier nommé **`data`** à la racine du projet.

---

### Création de l’environnement virtuel (recommandé)

Ouvrir un terminal dans le dossier du projet puis taper :

```bash
python -m venv env
env\Scripts\activate
```

Vous devriez voir **(env)** au début de la ligne.

---

### Installation des dépendances

Toujours dans le terminal :

```bash
pip install -r requirements.txt
```

### Lancer l’application Streamlit

Dans le terminal, à la racine du projet :

```bash
streamlit run app.py
```

Une page web va s’ouvrir automatiquement.

Si ce n’est pas le cas, ouvrir manuellement l’adresse indiquée, par exemple :

`http://localhost:8501`

---

### Pour arrêter l’application

Dans le terminal : **Ctrl + C**