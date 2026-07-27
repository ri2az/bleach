# Bleach Episode Tracker ⚔️

Une application web interactive et moderne conçue pour suivre sa progression dans l'animé **Bleach** (366 épisodes). L'outil permet de distinguer facilement les épisodes Canon, Semi-filler et Hors-série grâce à un système de codes couleurs clair.

## 🎨 Fonctionnalités

- **Suivi personnalisé** : Cochez les épisodes vus. Vos données sont sauvegardées automatiquement dans votre navigateur (`localStorage`).
- **Indicateurs visuels par type** :
  - 🟢 **Canon** (Vert)
  - 🟡 **Semi-filler** (Jaune)
  - 🔴 **Hors-série / Filler** (Rouge)
- **Barres de progression** : Suivez votre progression globale et celle de l'histoire principale (Canon + Semi-filler).
- **Filtres et Recherche** : Filtrez instantanément par type ou recherchez un épisode par son numéro.
- **Liens BetaSeries** : Chaque épisode propose un lien direct vers sa page officielle BetaSeries.
- **Export & Reset** : Possibilité d'exporter vos épisodes vus au format JSON ou de réinitialiser votre progression.

## 🛠️ Technologies utilisées

- **HTML5 / JavaScript (Vanilla)**
- **Tailwind CSS** (via CDN pour un design moderne et responsive)
- **FontAwesome** (pour les icônes)

---

## 🚀 Déploiement sur GitHub Pages

Suivez ces étapes simples pour héberger gratuitement votre tracker sur GitHub Pages :

1. **Créer un dépôt sur GitHub** :
   - Connectez-vous à votre compte GitHub et créez un nouveau dépôt (ex: `bleach-tracker`).
   - Laissez-le public (requis pour GitHub Pages gratuit).

2. **Ajouter le fichier principal** :
   - Assurez-vous que votre fichier HTML principal est renommé en **`index.html`**.
   - Uploadez ce fichier `index.html` à la racine de votre dépôt (via l'interface web de GitHub ou en ligne de commande).

3. **Activer GitHub Pages** :
   - Sur votre dépôt GitHub, allez dans l'onglet **Settings** (Paramètres).
   - Dans le menu de gauche, cliquez sur **Pages**.
   - Dans la section **Build and deployment** > **Branch** :
     - Sélectionnez la branche `main` (ou `master`).
     - Laissez le dossier sur `/ (root)`.
     - Cliquez sur **Save**.

4. **Accéder à votre application** :
   - Après quelques secondes, GitHub vous affichera l'URL publique de votre site en haut de la page (ex: `https://votre-pseudo.github.io/bleach-tracker/`).
   - Cliquez dessus pour profiter de votre tracker en ligne !

---

## 📝 Licence

Ce projet est open-source et mis à disposition pour les fans de Bleach.
