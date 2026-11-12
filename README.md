# Partenaire Biomédical

Application web de suivi du programme de contrôle qualité du SPECT/CT Siemens Symbia Pro.Specta X3, Hôpital Dogta-Lafiè, Lomé.

## Fichiers à mettre dans le dépôt GitHub (même dossier, tous ensemble)

- `index.html` (l'application, bibliothèque PDF intégrée)
- `manifest.webmanifest`, `sw.js` (installation et ouverture hors connexion)
- `icon-180.png`, `icon-192.png`, `icon-512.png`, `icon-maskable-512.png` (icônes)

Après le dépôt, ouvrir l'adresse GitHub Pages (https) : Chrome/Edge proposent d'installer l'application sur ordinateur et Android, Safari via Partager > Sur l'écran d'accueil.

## Profils et codes d'accès par défaut

| Profil | Code par défaut |
|---|---|
| Manipulateur | `manip2026` |
| Technicien biomédical | `bio2026` |

Changer les deux codes dès la première connexion (Réglages et aide).

## Plages et critères

Les valeurs préremplies (température 18 à 25 °C, humidité 20 à 75 %, gradient 4,4 °C/h) viennent du manuel Siemens ; les autres contrôles portent un critère qualitatif. Le technicien biomédical complète ou corrige chaque critère avec le bouton « Critère » du calendrier.

## Assistant qualité

Assistant à règles (sans connexion ni clé) : répond à une vingtaine de sujets issus des procédures, liste les retards, rédige un résumé copiable, et propose cause et action corrective dans une fiche de non-conformité (profil technicien). Il ne modifie jamais les données.
