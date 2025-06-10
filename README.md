# 🚀 Apprendre Bootstrap avec Vite

Bienvenue dans ce projet pédagogique qui vous guide pas à pas pour apprendre à utiliser **Bootstrap 5** dans un environnement moderne grâce à **Vite**.  
L'objectif est de vous montrer comment créer rapidement des sites web responsives et élégants, tout en profitant d'un workflow professionnel.

---

## 📚 Sommaire

- [🚀 Apprendre Bootstrap avec Vite](#-apprendre-bootstrap-avec-vite)
  - [📚 Sommaire](#-sommaire)
  - [Présentation du projet](#présentation-du-projet)
  - [Prérequis](#prérequis)
  - [Installation du projet](#installation-du-projet)
  - [Structure du projet](#structure-du-projet)
  - [Utilisation de Bootstrap](#utilisation-de-bootstrap)
  - [Lancement du serveur de développement](#lancement-du-serveur-de-développement)
  - [Personnalisation et extensions](#personnalisation-et-extensions)
  - [Ressources utiles](#ressources-utiles)
  - [Conseils pédagogiques](#conseils-pédagogiques)

---

## Présentation du projet

Ce projet a été conçu pour illustrer l'intégration de Bootstrap dans un projet moderne avec Vite.  
Vous y trouverez :
- Une page d'accueil avec des sections typiques (navbar, hero, cards, call-to-action, footer)
- L'utilisation de composants Bootstrap et d'icônes Bootstrap Icons
- Un point de départ pour vos propres exercices et expérimentations

---

## Prérequis

- **Node.js** (version 16 ou supérieure recommandée)
- **npm** (généralement installé avec Node.js)

---

## Installation du projet

1. **Cloner le dépôt**  
   ```bash
   git clone <url-du-repo>
   cd cours-vite-bootstrap
   ```

2. **Installer les dépendances**  
   ```bash
   npm install
   ```

---

## Structure du projet

```
cours-vite-bootstrap/
│
├── index.html           # Page principale avec structure Bootstrap
├── tutoriel.html        # (À compléter) Page tutoriel sur l'installation de Bootstrap
├── src/
│   ├── main.js          # Point d'entrée JS, import de Bootstrap et des icônes
│   └── style.css        # Styles personnalisés (optionnels)
├── public/
│   └── vite.svg         # Favicon
├── package.json         # Dépendances et scripts npm
└── ...
```

---

## Utilisation de Bootstrap

- **Bootstrap** et **Bootstrap Icons** sont installés via npm et importés dans `src/main.js` :
  ```js
  import 'bootstrap/dist/css/bootstrap.min.css'
  import 'bootstrap/dist/js/bootstrap.bundle.min.js'
  import 'bootstrap-icons/font/bootstrap-icons.css'
  ```
- Vous pouvez utiliser toutes les classes et composants Bootstrap dans vos fichiers HTML en les reliant à main.js.
- Les icônes Bootstrap sont disponibles via la classe `bi bi-nomdelicone`.

---

## Lancement du serveur de développement

Pour démarrer le projet en mode développement (rechargement automatique) :
```bash
npm run dev
```
Le projet sera accessible sur [http://localhost:5173](http://localhost:5173) (ou un autre port indiqué dans le terminal).

Pour générer une version de production :
```bash
npm run build
```
Pour prévisualiser la version de production :
```bash
npm run preview
```

---

## Personnalisation et extensions

- **style.css** : Ajoutez vos propres styles pour personnaliser l'apparence au-delà de Bootstrap.
- **tutoriel.html** : Complétez cette page pour expliquer à vos élèves comment installer Bootstrap via un package manager, ou pour ajouter des exemples pratiques.
- **Exercices** : Ajoutez des sections ou des fichiers pour proposer des exercices à vos étudiants.

---

## Ressources utiles

- [Documentation officielle Bootstrap](https://getbootstrap.com/docs/5.3/getting-started/introduction/)
- [Bootstrap Icons](https://icons.getbootstrap.com/)
- [Vite Documentation](https://vitejs.dev/guide/)
- [Exemples de templates Bootstrap](https://getbootstrap.com/docs/5.3/examples/)

---

## Conseils pédagogiques

- **Expérimentez !** Modifiez le HTML, ajoutez des composants Bootstrap, changez les couleurs, testez la responsivité.
- **Lisez le code** : Observez comment les classes Bootstrap structurent la page.
- **Complétez le tutoriel** : Ajoutez vos propres explications ou guides pour aider vos camarades.

---

N'hésitez pas à adapter ce projet pour vos propres besoins pédagogiques !  
Bon apprentissage 🎓
