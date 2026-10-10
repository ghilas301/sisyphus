# The Eternal Push – Sisyphus Game (Jeu de Sisyphe)

Un jeu web absurde, rapide, international et rentable inspiré du mythe de Sisyphe et de la philosophie d'Albert Camus (*Le Mythe de Sisyphe*, 1942).

## 🚀 Démarrage Rapide en Local

### Prérequis
- Node.js (version 18 ou supérieure)
- npm ou yarn ou pnpm

### Installation & Lancement
```bash
# 1. Installer les dépendances
npm install

# 2. Lancer le serveur de développement local
npm run dev
```
Ouvrez ensuite votre navigateur sur **http://localhost:3000** (ou le port affiché).

### Build de Production
```bash
npm run build
```
Le dossier statique optimisé sera généré dans `dist/`.

## 🌐 Déploiement en 1 Clic (Gratuit)

### Sur Vercel :
```bash
npx vercel
```

### Sur Netlify :
```bash
npx netlify deploy --prod
```

### Sur GitHub Pages :
Vous pouvez déployer directement le dossier `dist/` généré après `npm run build`.

## 💰 Intégration Publicitaire (Adsterra)
1. Créez un compte éditeur sur [Adsterra](https://adsterra.com).
2. Créez un emplacement de bannière (300x250 ou 728x90).
3. Insérez votre script dans le conteneur réservé de l'écran de fin de partie (`src/components/GameOverModal.tsx`).
4. La zone est pré-dimensionnée pour garantir un score de stabilité visuelle **CLS ≤ 0,1**.

## 📱 PWA & Mode Hors-ligne
L'application inclut un `manifest.json` et un Service Worker (`sw.js`). Une fois installée sur mobile ou ordinateur, elle fonctionne 100% hors-ligne sans connexion internet.
