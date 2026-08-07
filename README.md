# TH2 Patrimoine - Site Web

Site web professionnel pour TH2 Patrimoine, cabinet de conseil et de stratégie en organisation patrimoniale.

## Structure du projet

```
TH2-Patrimoine/
├── index.html                 # Page d'accueil
├── css/
│   └── styles.css            # Styles CSS principaux
├── js/
│   └── main.js               # JavaScript principal
├── pages/
│   ├── assurance-vie.html    # Page Assurance-vie
│   ├── capitalisation.html   # Page Capitalisation
│   ├── per.html              # Page PER (Plan d'Épargne Retraite)
│   └── prevoyance.html       # Page Prévoyance
└── README.md                 # Documentation
```

## Fonctionnalités

### Pages principales
- **Accueil** : Présentation des solutions, témoignages, formulaire de contact
- **Assurance-vie** : Solutions d'épargne et de transmission
- **Capitalisation** : Investissement et croissance du capital
- **PER** : Préparation de la retraite avec avantages fiscaux
- **Prévoyance** : Protection des proches et couverture des aléas

### Caractéristiques techniques
- Design responsive (mobile, tablette, desktop)
- Navigation intuitive avec menu mobile
- Animations CSS et JavaScript
- Formulaires interactifs
- FAQ avec système d'accordéon
- Bouton "Retour en haut"

## Palette de couleurs

D'après l'analyse du site th2patrimoine.com, la palette utilisée est :
- **Bleu foncé** : #2c3e50 (couleur principale)
- **Bleu clair** : #3498db (couleur secondaire)
- **Rouge** : #e74c3c (couleur d'accent)
- **Gris clair** : #f8f9fa (arrière-plan)
- **Blanc** : #ffffff

## Utilisation

### Développement local
1. Clonez le dépôt
2. Ouvrez le fichier `index.html` dans votre navigateur
3. Naviguez entre les différentes pages via le menu

### Déploiement
- Copiez l'ensemble des fichiers sur votre serveur web
- Assurez-vous que la structure des dossiers est conservée
- Le site est prêt à être utilisé

## Personnalisation

### Modifier les couleurs
Éditez les variables CSS dans `css/styles.css` :
```css
:root {
    --primary-color: #2c3e50;
    --secondary-color: #3498db;
    /* ... */
}
```

### Ajouter une nouvelle page
1. Créez un nouveau fichier HTML dans le dossier `pages/`
2. Utilisez la même structure que les pages existantes
3. Ajoutez le lien dans le menu de navigation (dans `index.html` et les autres pages)

### Modifier le contenu
- Éditez directement les fichiers HTML pour modifier le contenu
- Les styles sont centralisés dans `css/styles.css`
- Les fonctionnalités JavaScript sont dans `js/main.js`

## Technologies utilisées

- HTML5
- CSS3 (Flexbox, Grid, Variables CSS)
- JavaScript (ES6+)
- Font Awesome (icônes)

## Compatibilité navigateurs

- Chrome (recommandé)
- Firefox
- Safari
- Edge
- Mobile (iOS, Android)

## Contact

Pour toute question ou demande de personnalisation, contactez TH2 Patrimoine :
- Téléphone : 01 59 03 05 74
- Email : contact@th2patrimoine.com
- Site : https://th2patrimoine.com/

## Licence

Ce projet est la propriété de TH2 Patrimoine. Toute reproduction ou utilisation non autorisée est interdite.
