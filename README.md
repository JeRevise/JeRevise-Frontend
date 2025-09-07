![JeRevise Banner](https://raw.githubusercontent.com/JeRevise/JeRevise/refs/heads/main/svgviewer-png-output.png)

# JeRevise - Frontend

Bienvenue sur le dépôt **JeRevise-Frontend**.  
Ce dépôt contient l’interface web de la plateforme **JeRevise**, conçue pour les collèges afin d’améliorer la révision des élèves grâce à des outils modernes, accessibles et interactifs.

---

## 🚀 Fonctionnalités principales

- **Interface élève** :
  - Connexion via le **CAS Mon ENT Occitanie** ou un CAS compatible.
  - Révision des matières par chapitres.
  - Accès aux QCM générés automatiquement par l’IA.
  - Suivi des résultats et progression.

- **Interface professeur** :
  - Upload de cours (PDF, images, scans).
  - Gestion des matières et chapitres.
  - Génération automatique de QCM via l’IA.
  - Dashboard de suivi des élèves.

---

## 🛠️ Stack technique

- **Framework frontend** : React (Next.js possible si besoin SSR/SEO).  
- **UI & style** : TailwindCSS + composants réactifs.  
- **API** : Connexion au backend Node.js (`JeRevise-Backend`).  
- **Auth** : Intégration CAS / ENT.  

---

## 📦 Installation et lancement

1. Cloner le repo :
```code
git clone https://github.com/JeRevise/JeRevise-Frontend.git
```

2. Installer les dépendances :
```code
npm install
```

3. Lancer en mode développement :
   3.1 Lancer en local :
   ```code
   npm run dev
   ```
   3.2 Lancer en accesible depuis Internet :
   ```code
   npm run dev -- --host
   ```
---

## 🤝 Contribution

Les contributions sont les bienvenues !  
Merci de lire le fichier `CONTRIBUTING.md` avant toute pull request.

---

## 📜 Licence

Projet open source sous licence **MIT**.
