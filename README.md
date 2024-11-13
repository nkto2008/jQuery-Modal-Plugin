# Modal Component

Ce projet contient un composant React de modal personnalisé.

## Prérequis

- **Node.js** : Version 14 ou supérieure recommandée.
  [Téléchargez Node.js ici](https://nodejs.org/).
- **NPM** : Version 6 ou supérieure recommandée (installée avec Node.js).
- **Éditeur de texte recommandé** :
  [Visual Studio Code](https://code.visualstudio.com/) pour une meilleure
  expérience de développement.

## Installation

1. **Cloner le dépôt** (si ce projet est versionné) :
   ```bash
   git clone <URL_du_dépôt>
   ```

2. **Naviguer dans le dossier du projet** :
   ```bash
   cd modal-package
   ```

3. **Installer les dépendances** :
   ```bash
   npm install
   ```

4. **Lancer le projet** : Utilisez la commande suivante pour démarrer le projet
   en mode développement :
   ```bash
   npm start
   ```

### Installation via npm

Pour installer ce package, vous pouvez également le récupérer via npm :

```bash
npm install modal-ocr-yani
```

## Utilisation

Le composant `Modal` peut être importé et utilisé dans vos composants React
comme suit :

```jsx
import Modal from "./Modal";

// Exemple d'utilisation
function App() {
    return (
        <div>
            <Modal isOpen={true} title="Exemple de modal">
                Contenu de la modal ici
            </Modal>
        </div>
    );
}

export default App;
```

## Scripts Disponibles

- `npm start` : Lance l'application en mode développement.
- `npm run build` : Génère une version optimisée du projet pour la production.

## Structure des Fichiers

- `Modal.jsx` : Composant React pour la modal.
- `Modal.css` : Styles CSS pour le composant modal.
- `index.js` : Point d'entrée principal du module.
