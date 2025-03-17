# node-js-dev-env

## Aperçu

js-dev-env est un environnement de développement Node.js préconfiguré pour créer des applications JavaScript avec React. Il offre une configuration complète incluant webpack, Babel, ESLint, Jest pour les tests et JSDoc pour la documentation.

## Fonctionnalités

- JavaScript moderne avec Babel
- Bundling de modules avec webpack
- Analyse de code avec ESLint (style Airbnb)
- Tests unitaires avec Jest (avec rapports de couverture)
- Génération de documentation avec JSDoc
- Formatage des commits avec Commitizen

## Démarrage

### Prérequis

- Node.js (v23.10.0)
- npm (v10.9.2)

### Installation

Exécutez la commande suivante pour installer les dépendances :

```bash
npm install
```

### Scripts Disponibles

- **`npm run dev`**  
  Démarre le serveur de développement avec rechargement à chaud.

- **`npm run prod`**  
  Compile l'application pour la production et exécute les tests par la suite.

- **`npm test`**  
  Exécute les tests unitaires avec Jest.

- **`npm run lint`**  
  Lance ESLint sur tous les fichiers JavaScript du répertoire source.

- **`npm run doc`**  
  Génère la documentation du projet avec JSDoc.

- **`npm run commit`**  
  Lance Commitizen pour des messages de commit standardisés.

### Structure du Projet

- **src/**  
  Contient le code source du projet.

- **test/**  
  Contient les fichiers de test et les rapports de couverture.

- **.gitignore**  
  Définit les fichiers et répertoires exclus du suivi Git.

### Configuration

- **Babel** : Configuré avec `@babel/preset-env` pour supporter le JavaScript moderne.
- **Webpack** : Compile et sert l'application.
- **ESLint** : Assure la qualité du code en suivant le guide de style Airbnb.
- **Jest** : Configuré pour l'exécution des tests et la collecte de la couverture.
- **JSDoc** : Génère la documentation du projet selon la configuration définie.

### Auteur

Abdouarrahmane FOUAD  
Ce projet est sous licence MIT.


