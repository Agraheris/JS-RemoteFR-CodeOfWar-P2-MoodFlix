MoodFlix 🎬

Une application de recommandation de films basée sur votre humeur

Hackathon Wild Code School - Équipe de 4 développeurs - Formation Wild Code School
MoodFlix est une plateforme innovante qui recommande des films en fonction de votre état d'esprit du moment. Sélectionnez votre humeur et découvrez des films parfaitement adaptés à vos envies !

✨ Fonctionnalités

Sélection d'humeur : Interface intuitive pour choisir votre état d'esprit
Recommandations personnalisées : Algorithme de suggestion basé sur l'humeur
Fiches détaillées : Informations complètes sur chaque film (synopsis, casting, notes)
Interface responsive : Expérience optimisée sur tous les appareils
Gestion des favoris : Sauvegardez vos films préférés

🛠️ Technologies utilisées
Frontend

React - Interface utilisateur dynamique
JavaScript ES6+ - Logique applicative
CSS3 - Styles et animations
Vite - Build tool et développement

Backend

Express.js - Serveur web Node.js
MySQL - Base de données relationnelle
Node.js - Environnement d'exécution

Outils

ESLint - Qualité du code
Prettier - Formatage du code
Harmonia - Framework Wild Code School

🚀 Installation et lancement
Prérequis

Node.js (version 14 ou supérieure)
MySQL
npm ou yarn

Installation

Cloner le repository

bashgit clone https://github.com/Agraheris/JS-RemoteFR-CodeOfWar-P2-MoodFlix.git
cd JS-RemoteFR-CodeOfWar-P2-MoodFlix

Installer les dépendances

bashnpm install

Configuration de l'environnement

bash# Copier les fichiers d'exemple
cp server/.env.sample server/.env
cp client/.env.sample client/.env

# Éditer les fichiers .env avec vos configurations

Configuration de la base de données

bash# Migrer la base de données
npm run db:migrate

# Peupler avec des données d'exemple
npm run db:seed

Lancement de l'application

bash# Développement (client + serveur)
npm run dev

# Ou séparément
npm run dev:client  # Port 3000
npm run dev:back    # Port 5000
📱 Utilisation

Accédez à l'application : Ouvrez votre navigateur sur http://localhost:3000
Sélectionnez votre humeur : Choisissez parmi les différentes humeurs proposées
Découvrez des films : Explorez les recommandations personnalisées
Ajoutez aux favoris : Sauvegardez vos films préférés pour plus tard

👥 Équipe de développement
Projet réalisé dans le cadre d'un hackathon à la Wild Code School par une équipe de 4 développeurs passionnés.
📄 Licence
Ce projet est sous licence MIT. Voir le fichier LICENSE pour plus de détails.
🤝 Contribution
Les contributions sont les bienvenues ! N'hésitez pas à :

Fork le projet
Créer une branche pour votre fonctionnalité (git checkout -b feature/AmazingFeature)
Commit vos changements (git commit -m 'Add some AmazingFeature')
Push vers la branche (git push origin feature/AmazingFeature)
Ouvrir une Pull Request


💡 Astuce : Pour une meilleure expérience, utilisez MoodFlix avec vos amis et comparez vos recommandations !
⭐ N'hésitez pas à mettre une étoile si ce projet vous plaît !
