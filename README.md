# GameCritics

Site web qui répertorie des jeux vidéo et où les joueurs peuvent donner leur avis.

Projet réalisé en **HTML** et **CSS**.

---

## Présentation

GameCritics est un petit site de 4 pages :

- une page d'accueil avec la liste des jeux et un formulaire pour donner son avis ;
- une page qui affiche les avis des joueurs ;
- une page de remerciement après l'envoi du formulaire.

## Fonctionnalités

- Affichage des jeux sous forme de cartes (nom, genre, description, note moyenne)
- Formulaire pour donner son avis (pseudo, jeu, note, commentaire)
- Page des avis avec des liens pour aller directement à un jeu
- Page de remerciement après l'envoi du formulaire
- Site **responsive** : il s'adapte aux tablettes et aux téléphones

## Structure du projet

```
gamecritics/
├── index.html       → page d'accueil (jeux + formulaire)
├── avis.html        → page des avis des joueurs
├── merci.html       → page de remerciement
├── css/
│   └── style.css    → feuille de style commune
└── README.md        → ce fichier
```

## Technologies utilisées

| Technologie | Utilisation |
|-------------|-------------|
| HTML5       | Structure des pages |
| CSS3        | Mise en forme et responsive (flexbox, media queries) |

Il n'y a pas de JavaScript dans ce projet.

## Lancer le projet

1. Télécharger ou cloner le projet :
   ```bash
   git clone https://github.com/ton-pseudo/gamecritics.git
   ```
2. Ouvrir le dossier `gamecritics`
3. Double-cliquer sur `index.html` pour l'ouvrir dans le navigateur

Aucune installation n'est nécessaire.

## Responsive

Le CSS contient deux `@media` :

- **768px et moins** (tablette) : 2 cartes par ligne
- **480px et moins** (téléphone) : 1 carte par ligne, menu en colonne

## Limites du projet

- Le formulaire n'enregistre pas les avis : il redirige seulement vers `merci.html`.
- Les jeux et les avis affichés sont écrits directement dans le code HTML.
- Pour que les avis s'ajoutent vraiment sur le site, il faudrait un langage côté serveur (PHP par exemple) et une base de données (MySQL).

## Améliorations possibles

- [ ] Enregistrer les avis dans une base de données
- [ ] Ajouter les avis automatiquement avec PHP
- [ ] Ajouter des images pour chaque jeu
- [ ] Calculer la note moyenne automatiquement
- [ ] Ajouter une barre de recherche

## 👤 Auteur

- ** ANG Thomas** — Création de la page index.html. Amélioration de la page style.css côté responsive
- ** THAI Julien** — Création du dépôt, page avis.html et merci.html et style.css

---
