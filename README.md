# Portfolio Personnel

Un portfolio professionnel moderne et responsive, développé en HTML5 et CSS3 vanilla, conçu pour être hébergé sur GitHub Pages.

![Portfolio Preview](assets/img/profil.jpg)

## 🚀 Caractéristiques

- **Design moderne et épuré** - Interface sobre type CV en ligne
- **100% Responsive** - Adapté aux mobiles, tablettes et desktops
- **Accessibilité** - Conforme aux standards WCAG (contraste, navigation clavier, ARIA)
- **Performance optimisée** - Code léger sans dépendances externes lourdes
- **SEO friendly** - Balises sémantiques HTML5 et meta tags optimisés
- **Animations subtiles** - Transitions fluides et effets au scroll

## 📁 Structure du projet

```
portfolio/
├── index.html          # Page principale
├── styles.css          # Feuille de styles
├── README.md           # Documentation
└── assets/
    └── img/
        └── profil.jpg  # Photo de profil
```

## 🛠️ Technologies utilisées

- **HTML5** - Structure sémantique
- **CSS3** - Flexbox, Grid, Variables CSS, Media Queries
- **Google Fonts** - Police Inter
- **Aucun framework** - Code pur pour une meilleure compréhension

## 📱 Sections incluses

1. **Hero** - Présentation avec photo, titre et liens sociaux
2. **À propos** - Description personnelle et informations clés
3. **Compétences** - Technologies et outils maîtrisés
4. **Expériences** - Parcours professionnel avec timeline
5. **Projets** - Portfolio de réalisations avec cartes interactives
6. **Formation** - Diplômes et certifications
7. **Contact** - Formulaire et coordonnées

## 🚀 Déploiement sur GitHub Pages

### 1. Créer un dépôt GitHub

```bash
# Sur GitHub, créez un nouveau dépôt nommé "portfolio"
# OU utilisez la ligne de commande :
curl -u 'votre-username' https://api.github.com/user/repos -d '{"name":"portfolio"}'
```

### 2. Initialiser et pousser le code

```bash
# Dans le dossier du projet
cd portfolio

# Initialiser Git
git init

# Ajouter les fichiers
git add .

# Créer le premier commit
git commit -m "Initial commit - Portfolio v1.0"

# Connecter au dépôt distant
git remote add origin https://github.com/votre-username/portfolio.git

# Pousser le code
git push -u origin main
```

### 3. Activer GitHub Pages

1. Allez sur votre dépôt GitHub
2. Cliquez sur **Settings** (Paramètres)
3. Dans le menu de gauche, cliquez sur **Pages**
4. Dans "Source", sélectionnez **Deploy from a branch**
5. Choisissez la branche **main** et le dossier **/(root)**
6. Cliquez sur **Save**

Votre portfolio sera accessible à l'adresse :
`https://votre-username.github.io/portfolio/`

## 🎨 Personnalisation

### Modifier les informations personnelles

Éditez le fichier `index.html` et remplacez :

- **Nom** : Ligne 73, remplacez "Alexandre Martin"
- **Titre** : Ligne 74, remplacez "Développeur Web Full Stack"
- **Description** : Lignes 75-77, modifiez le texte de présentation
- **Email** : Remplacez `contact@example.com` par votre email
- **Liens sociaux** : Modifiez les URLs GitHub et LinkedIn

### Changer la photo de profil

Remplacez le fichier `assets/img/profil.jpg` par votre propre photo.

### Modifier les couleurs

Dans `styles.css`, modifiez les variables CSS en début de fichier :

```css
:root {
    --color-primary: #2563eb;        /* Bleu principal */
    --color-primary-dark: #1d4ed8;   /* Bleu foncé */
    --color-accent: #06b6d4;         /* Cyan accent */
    /* ... */
}
```

### Modifier les projets

Dans `index.html`, section "Projets" (ligne ~290), modifiez chaque `article` avec :
- Le nom du projet
- La description
- Les technologies utilisées
- Les liens GitHub et démo

## 💻 Lancer en local

### Méthode simple

Ouvrez simplement le fichier `index.html` dans votre navigateur.

### Avec un serveur local (recommandé)

```bash
# Avec Python 3
python -m http.server 8000

# Avec Node.js (npx)
npx serve

# Avec PHP
php -S localhost:8000
```

Puis accédez à `http://localhost:8000`

## 🔧 Développement

### Structure CSS

Le fichier `styles.css` est organisé en sections :

1. **Variables CSS** - Couleurs, typographie, espacements
2. **Reset et base** - Styles de base
3. **Navigation** - Barre de navigation fixe
4. **Hero** - Section d'accueil
5. **Boutons** - Styles des boutons
6. **Sections** - Styles des différentes sections
7. **Animations** - Keyframes
8. **Responsive** - Media queries
9. **Accessibilité** - Styles pour l'accessibilité

### Points de rupture responsive

- **Desktop** : > 1024px
- **Tablette** : 768px - 1024px
- **Mobile** : < 768px
- **Petit mobile** : < 480px

## ♿ Accessibilité

Le portfolio respecte les bonnes pratiques d'accessibilité :

- ✅ Navigation au clavier complète
- ✅ Attributs `alt` sur toutes les images
- ✅ Contraste suffisant (WCAG AA)
- ✅ Structure sémantique HTML5
- ✅ ARIA labels sur les éléments interactifs
- ✅ Support du mode réduit de mouvement
- ✅ Skip links pour navigation rapide

## 📄 Licence

Ce projet est sous licence MIT. Vous êtes libre de l'utiliser, le modifier et le distribuer.

## 🙏 Crédits

- Icônes : [Heroicons](https://heroicons.com/)
- Police : [Google Fonts - Inter](https://fonts.google.com/specimen/Inter)

---

**Note** : N'oubliez pas de remplacer toutes les informations personnelles et de mettre à jour les liens vers vos propres profils sociaux et projets avant de publier votre portfolio !
