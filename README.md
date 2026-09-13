# App Docs

Politiques de confidentialité et documents légaux pour mes applications Android. Servi via GitHub Pages : https://hugo291.github.io/app-docs/

## Apps

| App | FR | EN | Autres |
|---|---|---|---|
| Triple 20 | [Confidentialité](https://hugo291.github.io/app-docs/triple-20/privacy.html) | [Privacy](https://hugo291.github.io/app-docs/triple-20/privacy.en.html) | |
| Journal 52 Moments | [Confidentialité](https://hugo291.github.io/app-docs/journal-52-moments/privacy.html) | [Privacy](https://hugo291.github.io/app-docs/journal-52-moments/privacy.en.html) | |
| Routine Five | [Confidentialité](https://hugo291.github.io/app-docs/routine-five/privacy.html) | [Privacy](https://hugo291.github.io/app-docs/routine-five/privacy.en.html) | |
| MiniGeste | | [Privacy](https://hugo291.github.io/app-docs/minigeste/privacy.html) | |
| Charge Mentale | [Confidentialité](https://hugo291.github.io/app-docs/charge-mentale/privacy.html) | [Privacy](https://hugo291.github.io/app-docs/charge-mentale/privacy.en.html) | |
| Sudoku Malin | [Confidentialité](https://hugo291.github.io/app-docs/sudoku-malin/privacy.html) | [Privacy](https://hugo291.github.io/app-docs/sudoku-malin/privacy.en.html) | |
| Nonogrammes | [Confidentialité](https://hugo291.github.io/app-docs/nonogrammes/privacy.html) | [Privacy](https://hugo291.github.io/app-docs/nonogrammes/privacy.en.html) | |
| Le Livre de Recettes de Famille | [Confidentialité](https://hugo291.github.io/app-docs/livre-recettes-famille/privacy.html) | [Privacy](https://hugo291.github.io/app-docs/livre-recettes-famille/privacy.en.html) | |
| Code Duo | [Confidentialité](https://hugo291.github.io/app-docs/code-duo/privacy.html) | [Privacy](https://hugo291.github.io/app-docs/code-duo/privacy.en.html) | |
| Carte Sonore | [Confidentialité](https://hugo291.github.io/app-docs/carte-sonore/privacy.html) | [Privacy](https://hugo291.github.io/app-docs/carte-sonore/privacy.en.html) | |
| DashFit | [Confidentialité](https://hugo291.github.io/app-docs/dashfit/privacy.html) | [Privacy](https://hugo291.github.io/app-docs/dashfit/privacy.en.html) | |
| Memoria | [Confidentialité](https://hugo291.github.io/app-docs/memoria/privacy.html) | [Privacy](https://hugo291.github.io/app-docs/memoria/privacy.en.html) | |
| Quittes | [Confidentialité](https://hugo291.github.io/app-docs/quittes/privacy.html) | [Privacy](https://hugo291.github.io/app-docs/quittes/privacy.en.html) | |
| Guestleaf (Bon séjour) | [Confidentialité](https://hugo291.github.io/app-docs/welcome-home/privacy.html) | [Privacy](https://hugo291.github.io/app-docs/welcome-home/privacy.en.html) | |
| Verba | [Confidentialité](https://hugo291.github.io/app-docs/verba/privacy.html) | [Privacy](https://hugo291.github.io/app-docs/verba/privacy.en.html) | [Suppression du compte](https://hugo291.github.io/app-docs/verba/delete-account.html) |
| Cadrans (Wear OS) | [Confidentialité](https://hugo291.github.io/app-docs/cadrans-wear/privacy.html) | [Privacy](https://hugo291.github.io/app-docs/cadrans-wear/privacy.en.html) | + une page par cadran (voir dossier) |
| Rayon | [Confidentialité](https://hugo291.github.io/app-docs/rayon/privacy.html) | [Privacy](https://hugo291.github.io/app-docs/rayon/privacy.en.html) | |
| Anagramme chrono | [Confidentialité](https://hugo291.github.io/app-docs/anagramme-chrono/privacy.html) | [Privacy](https://hugo291.github.io/app-docs/anagramme-chrono/privacy.en.html) | |
| Tri liquide | [Confidentialité](https://hugo291.github.io/app-docs/tri-liquide/privacy.html) | [Privacy](https://hugo291.github.io/app-docs/tri-liquide/privacy.en.html) | |
| Sudoku Classique | [Confidentialité](https://hugo291.github.io/app-docs/sudoku-classique/privacy.html) | [Privacy](https://hugo291.github.io/app-docs/sudoku-classique/privacy.en.html) | |
| Le Compte y est | [Confidentialité](https://hugo291.github.io/app-docs/compte-y-est/privacy.html) | [Privacy](https://hugo291.github.io/app-docs/compte-y-est/privacy.en.html) | |
| Ponts | [Confidentialité](https://hugo291.github.io/app-docs/ponts/privacy.html) | [Privacy](https://hugo291.github.io/app-docs/ponts/privacy.en.html) | |
| Yam's | [Confidentialité](https://hugo291.github.io/app-docs/yams/privacy.html) | [Privacy](https://hugo291.github.io/app-docs/yams/privacy.en.html) | |
| Embouteillage | [Confidentialité](https://hugo291.github.io/app-docs/embouteillage/privacy.html) | [Privacy](https://hugo291.github.io/app-docs/embouteillage/privacy.en.html) | |
| Le Détective Logique | [Confidentialité](https://hugo291.github.io/app-docs/detective-logique/privacy.html) | [Privacy](https://hugo291.github.io/app-docs/detective-logique/privacy.en.html) | |
| Wordspot | [Confidentialité](https://hugo291.github.io/app-docs/wordspot/privacy.html) | [Privacy](https://hugo291.github.io/app-docs/wordspot/privacy.en.html) | |

L'index public (`index.html`) reste la source de vérité pour la liste affichée aux utilisateurs ; ce tableau la reflète pour la lecture sur GitHub.

## Structure

```
app-docs/
├── index.html                      (page d'accueil publique, liste toutes les apps)
├── README.md
├── <app-slug>/
│   ├── privacy.html                (FR, sauf mention contraire)
│   ├── privacy.en.html             (EN)
│   └── ...                         (documents additionnels : suppression de compte, etc.)
├── cadrans-wear/                   (Wear OS : un cadran = une page de confidentialité dédiée)
│   ├── privacy.html / privacy.en.html   (app globale)
│   └── <cadran>.html               (un fichier par cadran, ex. aquarelle.html, kawaiidragons.html…)
└── verba/
    └── delete-account.html         (procédure de suppression de compte)
```

## Ajouter une nouvelle app

1. Créer un dossier `<app-slug>/`.
2. Ajouter `privacy.html` (FR) et `privacy.en.html` (EN), plus tout document légal complémentaire.
3. Ajouter une entrée dans `index.html` (section `<h2>` + liens).
4. Mettre à jour le tableau ci-dessus dans ce README.
