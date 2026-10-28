# 🏁 Drapeaux – le jeu

Jeu de drapeaux pour le hub **ChadGangGames** : un drapeau s'affiche, devine le pays.

## Modes
- **Solo** : Classique (20 drapeaux), Contre-la-montre (60 s), Survie (3 vies), Entraînement (sans chrono, avec les capitales).
- **En ligne** (dans le hub) : 2 à 8 joueurs, même drapeau pour tout le monde, bonus pour le plus rapide, classement entre chaque manche, podium.

## Difficultés
| | Pays | Réponse | Temps | Points |
|---|---|---|---|---|
| 🙂 Facile | 50 très connus | 4 propositions | 15 s | ×1 |
| 😏 Moyen | 91 | 4 propositions piégeuses | 12 s | ×1,5 |
| 😤 Difficile | 197 | à taper, 3 essais + indice | 20 s | ×2 |
| 💀 Expert | 197 + 35 territoires | à taper, 2 essais, drapeau zoomé/flouté/caché | 15 s | ×3 |

Filtre par continent possible. Les parties « Monde entier » comptent dans les classements du hub.

## Fichiers
- `index.html` : tout le jeu (HTML, CSS, JS). La liste des pays est en haut du script (`RAW`).
- `flags/` : drapeaux SVG du projet [flag-icons](https://github.com/lipis/flag-icons) (licence MIT, voir `flags/LICENSE.txt`).
- `fonts/` : Lilita One et Nunito (licence SIL OFL).
- `chadgang.json` + `cover.png` : fiche du jeu dans le hub.
