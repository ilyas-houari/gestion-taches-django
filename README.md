# Gestion des tâches étudiants

Mini-projet réalisé avec Django et Python permettant aux étudiants de gérer leurs tâches.

## Fonctionnalités

- Inscription
- Connexion et déconnexion
- Affichage des tâches
- Ajout d'une tâche
- Modification d'une tâche
- Suppression d'une tâche
- Statuts : À faire, En cours, Terminée
- Chaque utilisateur possède ses propres tâches
- Interface d'administration Django

## Technologies

- Python
- Django
- HTML
- CSS
- SQLite

## Applications Django

- accounts : gestion des utilisateurs et de l'authentification
- tasks : gestion des tâches

## Installation

```bash
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver