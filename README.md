# TheLabo-A           © Daniel Mancero Baquerizo 2026 - CRD d'Évry
# Entraînement rythmique V10

Petit jeu pédagogique d'entraînement à la reconnaissance rythmique, utilisable directement dans un navigateur web.
                            
## Fichiers

Placez ces trois fichiers dans le même dossier :

- `index.html` : structure du jeu
- `style.css` : présentation graphique
- `app.js` : logique du jeu, rythmes et audio

## Utilisation

1. Téléchargez les trois fichiers.
2. Conservez-les dans le même dossier.
3. Ouvrez `index.html` dans un navigateur récent.
4. Choisissez la subdivision puis la mesure.
5. Écoutez le rythme et choisissez la bonne proposition A, B ou C.

## Fonctionnement

- Mesures : 2/4, 3/4, 4/4 et 6/8
- 10 questions par manche
- Passage automatique après une bonne réponse
- Correction affichée après une mauvaise réponse
- Score en temps réel
- Récompense spéciale pour un score de 10/10
- Bouton pour rejouer
- Clavier : A, B, C pour répondre et espace pour réécouter

## Son

Le son est généré directement par le navigateur avec la Web Audio API. Aucun fichier audio externe n'est nécessaire.

## Installation

Aucune installation de Python n'est nécessaire. Le jeu fonctionne côté navigateur avec HTML, CSS et JavaScript.

## Structure

```text
jeu-rythmique-v10/
├── index.html
├── style.css
├── app.js
└── README.md
jeu pédagogique de reconnaissance rythmique
