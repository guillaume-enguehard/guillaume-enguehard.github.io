# Site portfolio de Guillaume Enguehard — consignes

Site statique publié par GitHub Pages depuis la branche `main` :
https://guillaume-enguehard.github.io

## Structure
- `index.html` : version anglaise (par défaut). `fr/index.html` : version française.
  Toute modification de contenu se fait dans les deux langues.
- `assets/style.css` : feuille de style unique. Réutiliser les classes existantes,
  ne pas ajouter de styles en ligne dans les pages.
- `games/<nom>/` : un dossier par jeu (visuel `cover.svg`, jeu en ligne dans `play/`,
  règles et livrets en PDF).
- `sitemap.xml` : y ajouter chaque nouvelle page.

## Ajouter un jeu
- Recopier le modèle de fiche en commentaire dans la section `games`
  (`<article class="game">`), dans `index.html` et `fr/index.html`.
- **Le nom du jeu s'écrit toujours en MAJUSCULES** : dans le titre de la fiche (`<h3>`),
  dans le `<title>` et le `<h1>` des pages du jeu, et partout où il sert de titre.
- Visuel au format 16:10 ou 4:3, montré en entier dans la fiche.
- Trois accès par jeu : « Play online » / « Jouer en ligne » (bouton principal),
  puis les règles et le livret en liens secondaires.

## Style
- La lisibilité passe avant tout : police Atkinson Hyperlegible Next, texte grand et contrasté.
- Vérifier le rendu sur ordinateur et sur téléphone avant de publier.
