# Simple projet Python : Découverte Data Engineering
## Description
Ce projet est un projet de découverte de Data Engineering. Il a pour but de mettre en place un pipeline de traitement de données.
Nous chargeons un fichier.csv qui contient des utilisateurs et leurs informations. Nous allons ensuite le traiter pour en extraire des informations, puis les stocker dans une base de données.
## Prérequis
- Python 3.7
- Docker
- Docker-compose
## Installation
- Cloner le projet
- Créer un environnement virtuel
    ```bash
    # Linux
    python -m venv .venv
    # Windows
    py -m venv .venv
    ```
- Activer l'environnement virtuel
    ```bash
    # Linux
    .venv/bin/activate
    # Windows (batch/cmd)
    .venv/Scripts/activate.bat
    # Windows (powershell)
    .venv/Scripts/Activate.ps1
    ```
- Installer les dépendances
```bash
pip install -r requirements.txt
```
# Mettre un lien
[lien google]

# Mettre des images
![Mon image]

# Initialiser
```bash
git flow init
```
git remote add origin url

git branch

# selctionner les fichiers que je veux sauvegarder sur github

```bash
git add # selectionner les fichiers à sauvegarder
```
```bash
git commit -am "erreur" # sauvegarder et nommer le nom de la sauvegarde
```
# copie de l'historique et le partager avec mon équipe
```bash
git push --all
```
# retrouver toutes les sauveagardes (commit = sauvegarde)
```bash
gitk # retrouver tous les fichiers sauvegardés avec les différentes version
```
# changer de branch

```bash
git checkout main # aller dans la branche main
```
# Installer PIP install

```bash
pip install pandas pymysql
```
# Récupérer les dépendaces
```bash
pip freeze > requirements.txt #récupère toutes les dépendances que tu as installer avec les versions exactes
```
