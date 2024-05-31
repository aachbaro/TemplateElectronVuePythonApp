Template pour une application Vue Electron vuetify et python pour le backend

Cote backend: (windows)
# Créer un nouvel environnement virtuel
python -m venv env

# Activer le nouvel environnement virtuel
.\env\Scripts\Activate

# Installer les dépendances à partir de requirements.txt
pip install -r requirements.txt

# Lancer le serveur Flask
flask run

Cote frontend:
# installer les dependances
npm install
# Lancer l'application
npm run electron:serve
