# 🌍💬 Projet Waxma - README

## 📝 Description

Waxma est une application innovante qui utilise des images satellites et des modèles IA pour rendre les données démographiques, socio-économiques et géospatiales accessibles à tous. À travers un chatbot interactif, Waxma offre :

- 🗺 Cartes thématiques : Codes couleur universels et icônes compréhensibles.
- 📊 Visualisations intuitives : Statistiques sous forme de tableaux et graphiques.
- 🤖 Interactions intelligentes : Réponses instantanées aux requêtes via un chatbot.

---

## 🚀 Pré-requis

- Python 3.9 ou supérieur
- Node.js (version recommandée : 18.x ou supérieure)
- npm ou yarn
- Virtualenv pour gérer l’environnement virtuel du backend

---

## ⚙️ Installation et lancement

### 1️⃣ Cloner le projet

- Exécutez la commande suivante dans votre terminal :
```git clone https://github.com/votre-repo/waxma.git ```
```cd waxma```


---

### 2️⃣ Configurer le Backend (Django)

1. Accédez au dossier `backend` :
```cd waxma```

2. Créez un environnement virtuel :
```python -m venv venv```

3. Activez l’environnement virtuel :
- Sous Windows :
  ```
  venv\Scripts\activate
  ```
- Sous Linux/Mac :
  ```
  source venv/bin/activate
  ```

4. Installez les dépendances nécessaires :
```pip install -r requirements.txt```

5. Appliquez les migrations de la base de données :
```
python manage.py makemigrations
python manage.py migrate
```

6. Lancez le serveur Django :
```python manage.py runserver```

- 💡 Le backend est maintenant disponible à l’adresse [http://127.0.0.1:8000](http://127.0.0.1:8000).

---

### 3️⃣ Configurer le Frontend (Next.js)

1. Accédez au dossier `frontend` :
```cd interface```

2. Installez les dépendances nécessaires :
```npm install```

3. Lancez le serveur de développement :
```npm run dev```

- 💡 Le frontend est accessible à l’adresse [http://localhost:3000](http://localhost:3000).

---

### 4️⃣ Configurer les fichiers d’environnement

- Backend (`waxma/.env`) :
```SECRET_KEY=Votre_Clé_Secrète```


---

## 🏗 Structure du projet

waxma/ ├── waxma/ # Interface │ ├── manage.py # Commande principale Django │ ├── requirements.txt │ ├── .env/ # Environnement virtuel ├── interface/ # Next.js │ ├── pages/ # Pages du site │ ├── components/ # Composants réutilisables │ ├── package.json # Dépendances du projet


---

## 📋 Commandes utiles

### Backend

- Pour activer l’environnement virtuel :
  - Sous Windows :
    ```
    venv\Scripts\activate
    ```
  - Sous Linux/Mac :
    ```
    source venv/bin/activate
    ```

- Pour désactiver l’environnement virtuel :
```deactivate```

---

### Frontend
- Pour lancer l’application en mode production :
```npm run dev```


---

## 🤝 Contribuer

1. Forkez le projet :
```
git fork https://github.com/Gothouteno/waxma.git
```

2. Créez une branche pour votre fonctionnalité :
```git checkout -b ma-nouvelle-fonctionnalité```

3. Committez vos modifications :
```git commit -m "Ajout de ma fonctionnalité"```

4. Poussez vos modifications :
```git push origin ma-nouvelle-fonctionnalité```


5. Créez une pull request sur GitHub.

---

## 📞 Contact

Créateur : Andre Sarr 
Email : replit005@gmail.com

---

## 📜 Licence

Ce projet est sous licence MIT. Consultez le fichier `LICENSE` pour plus d’informations.
