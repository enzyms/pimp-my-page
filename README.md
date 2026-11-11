# Pimp My Page

Plateforme d'initiation HTML/CSS pour l'atelier « dev frontend » de Futur en tous genres (12.11.2026), 90 minutes, filles de 13–14 ans.

Chaque participante code sa carte de profil en 10 missions guidées (validation automatique), puis l'emporte sur son natel via un QR code. Deux bonus pour les plus rapides : une animation, et une 2e page (`page2.html`, même CSS) reliée par des liens.

## Fonctionnement

- Un seul fichier, `index.html`, sans build ni dépendance à installer.
- Le travail est sauvegardé dans le `localStorage` du navigateur.
- **📱 Sur mon natel** : le code est compressé dans le lien (`#c=…`). Aucun serveur, aucun compte, aucune donnée stockée. Le site doit donc rester en ligne à la même adresse pour que les QR codes continuent de marcher.
- **🖼️ Images** : galerie de 53 photos et 40 stickers hébergés dans `img/`, insérés au curseur.
- **CodePen ↗** ouvre le code dans CodePen, pré-rempli, sans compte.

## En local

```bash
python3 -m http.server 8765
```

Puis ouvrir http://localhost:8765.

## Avant l'atelier

Remettre un laptop à zéro : ouvrir l'adresse du site avec `#reset` à la fin.

## Crédits images

- Photos (`img/*.jpg`) : [Unsplash](https://unsplash.com), licence Unsplash.
- Stickers (`img/stickers/*.svg`) : [OpenMoji](https://openmoji.org), licence CC BY-SA 4.0.

Les images sont servies par le site lui-même, pour que la galerie marche même sur un réseau qui bloque les sites externes.
