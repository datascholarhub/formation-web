# Exercice Séance 4 : Portion de page Crunchyroll

## Objectifs

Recréer le design d'une portion d'une page de Crunchyroll en HTML et CSS. Cet exercice vous permettra de :

- Mettre en pratique votre maîtrise des balises HTML sémantiques
- Utiliser les propriétés CSS pour styliser une page web
- Seule la version mobile est demandée pour cet exercice (veuillez redimensionner pour vous assurer que votre design est adapté)

## Résultat Attendu

Votre page doit ressembler à l'image fournie dans le dossier `attendu/index.png`.


## Contenu

Le contenu textuel à utiliser se trouve dans le dossier `contenus-textuels/index.txt`.

## Ressources et Astuces

### Logo SVG Crunchyroll
Pour insérer le logo, vous pouvez utiliser le SVG directement dans votre HTML pour pouvoir modifier sa couleur :

```html
<svg class="header-logo-mobile" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 48 48" data-t="crunchyroll-logo-only-svg" aria-hidden="true" role="img">
  <path d="M5.818 26.871c.01-11.65 9.466-21.086 21.117-21.073 11.153.01 20.275 8.678 21.022 19.638.028-.467.043-.94.043-1.413C48.014 10.77 37.28.013 24.024 0 10.768-.014.014 10.721 0 23.976-.014 37.23 10.721 47.987 23.976 48c.548 0 1.092-.018 1.63-.054-11.051-.676-19.8-9.856-19.788-21.076Zm32.568.312a8.2 8.2 0 0 1-8.19-8.208 8.204 8.204 0 0 1 5.424-7.71 17.923 17.923 0 0 0-8.375-2.073c-9.95-.01-18.022 8.047-18.032 17.995-.01 9.95 8.047 18.022 17.995 18.033 9.948.01 18.022-8.047 18.032-17.997 0-1.127-.103-2.23-.301-3.301a8.187 8.187 0 0 1-6.554 3.261h.001Z"></path>
</svg>
```

### Icônes Bootstrap
Pour les flèches et autres icônes, utilisez Bootstrap Icons en ajoutant ce lien dans la section `<head>` :

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.10.5/font/bootstrap-icons.css">
```

Puis utilisez l'icône flèche avec :
```html
<i class="bi bi-arrow-down-short"></i>
```

## Palettes de Couleurs
Voici les couleurs utilisées dans le design :
-  #ff4600
-  #ff5000
-  #000000
-  #ffffff
-  #bbbbbb

## Fichiers attendus

Compressez votre travail dans un fichier ZIP et soumettez-le via Google Classroom. Assurez-vous que votre fichier ZIP contient au moins les fichiers suivants :
- `index.html` : Le fichier HTML de votre page de landing.
- `styles.css` : Le fichier CSS pour styliser votre page.
Si vous avez utilisé d'autres images ou d'autres ressources, incluez-les également dans le ZIP.
