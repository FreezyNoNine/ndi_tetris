# 🎮 Tetris en Node.js

Ce projet est une version simple du célèbre jeu **Tetris**, développée en **Node.js**.

🕹️ **Petit fun fact** : Ce jeu a été conçu à l'origine comme un **easter egg** pour notre projet de la **Nuit de l'Info 2023**. Lorsqu'un utilisateur tapait une URL incorrecte, au lieu d'afficher une erreur classique, nous lui offrions une petite partie de Tetris pour détendre l’atmosphère !

---

## 🚀 Lancer le projet

### 1. Cloner le dépôt

```bash
git clone https://github.com/FreezyNoNine/ndi_tetris.git
cd ndi_tetris
```

### 2. Installer les dépendances

```bash
npm install
```

### 3. Lancer l'application

```bash
node app.js
```

### 4. Accéder au jeu

Ouvre ton navigateur à l'adresse suivante :

```
http://localhost:3000
```

---

## 🛠️ Stack technique

- Node.js  
- Express
- HTML / CSS / JS côté client

---

## 💡 Contexte : Nuit de l'Info 2023

Ce projet faisait partie d’un plus gros site développé durant la **Nuit de l’Info 2023**.  
On voulait marquer les esprits, alors on a intégré ce Tetris comme **easter egg** accessible uniquement via une URL invalide. Original, non ? 😉

---

## 📂 Structure du projet

```
ndi_tetris/
├── public/
│   ├── img/
│   │   ├── retour1.jpg
│   │   ├── g_block.png
│   │   ├── r_block.png
│   │   └── y_block.png
│   ├── font/
│   │   └── modern-tetris.ttf
│   ├── style404.css
│   └── script404.js
├── views/
│   └── 404.ejs
├── controllers/
│   └── controllers.js
├── routes/
│   └── routes.js
├── package.json
├── package-lock.json
├── app.js
├── .gitignore
└── README.md
```

---

## 📄 Licence

Ce projet est open-source. N’hésitez pas à l’adapter, le modifier ou simplement à jouer avec 🎉

---

## 🙌 Crédits

Développé lors de la **Nuit de l’Info 2023** par notre équipe de choc 💪
