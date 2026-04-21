# Exercice - Seance 1

## Objectif
Reproduire un mini-site web de 2 pages en HTML/CSS a partir des contenus fournis.

Le site concerne le collectif CRISTAL (ENSPD) et doit inclure :
- une page d'accueil (`index.html`)
- une page de contact (`contacts.html`)

## Structure du dossier

```text
exercices/seance1/
├── attendu/
│   ├── contacts/
│   │   └── contacts-page.png
│   └── index/
│       ├── index-page-1.png
│       ├── index-page-2.png
│       └── index-page-3.png
├── contenus-textuels/
│   ├── contacts.txt
│   └── index.txt
└── images/
    ├── atelier-formation.png
    ├── communaute.png
    ├── logiciels-stats.png
    └── logo-cristal.png
```

## Ressources a utiliser
- Les textes se trouvent dans :
  - `contenus-textuels/index.txt`
  - `contenus-textuels/contacts.txt`
- Les illustrations se trouvent dans :
  - `images/`
- Le rendu visuel attendu est montre dans :
  - `attendu/index/`
  - `attendu/contacts/`

## Travail demande
1. Creer les fichiers du projet (dans un dossier de travail de votre choix) :
   - `index.html`
   - `contacts.html`
   - `styles.css`
2. Integrer tout le contenu du fichier `index.txt` dans la page d'accueil.
3. Integrer tout le contenu du fichier `contacts.txt` dans la page de contact.
4. Lier les deux pages entre elles avec des liens de navigation.
5. Inserer correctement les images indiquees dans les sections.

## Contraintes techniques minimales
- Utiliser une structure HTML semantique : `header`, `main`, `section`, `footer`.
- Utiliser des titres hierarchises (`h1`, `h2`, etc.).
- Ajouter des attributs `alt` pertinents pour toutes les images.
- Le formulaire de `contacts.html` doit contenir :
  - Nom et Prenoms
  - Adresse e-mail
  - Message (zone multiligne)
  - Bouton d'envoi
- Verifier que les liens et chemins vers les fichiers fonctionnent.

## Methode conseillee
1. Commencer par la structure HTML des 2 pages sans style.
2. Ajouter les contenus textuels complets.
3. Integrer les images.
4. Comparer avec les images de reference dans `attendu/` et ajuster.

## Verification finale (checklist)
- [ ] `index.html` s'affiche correctement.
- [ ] `contacts.html` s'affiche correctement.
- [ ] Navigation fonctionnelle entre les deux pages.
- [ ] Toutes les images sont visibles.
- [ ] Le formulaire est present et complet.
- [ ] Le rendu est proche des captures d'ecran du dossier `attendu`.

