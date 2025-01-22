# My WordPress Project

Ce projet configure une instance WordPress avec une base de données MySQL en utilisant Docker Compose.

## Structure du projet

my-wordpress-project/ 
├── docker-compose.yml 
├── .gitignore 
├── README.md 
├── secrets/
│ ├── db_root_password.txt 
│ ├── db_password.txt 
├── data/ 
│ ├── db/ # Contient les données MySQL 
│ ├── wp/ # Contient les fichiers WordPress

## Prérequis

- Docker installé sur votre machine
- Docker Compose installé

## Installation et utilisation

1. **Clonez le dépôt :**
   ```bash
   git clone https://github.com/<your_username>/<repository_name>.git
   cd my-wordpress-project
   echo "your_root_password" > secrets/db_root_password.txt
echo "your_db_password" > secrets/db_password.txt

docker compose up -d

Accédez à WordPress : Ouvrez votre navigateur et accédez à http://localhost.
