# robux-giveaway-bot
Bot Discord qui récompense l'activité et l'aide par des giveaway Robux.


## Commandes principales

- `!profile` : Affiche ton XP, help points et tokens disponibles.
- `!tokens` : Affiche le nombre de tokens disponibles.
- `!creategiveaway <prize> | <cost> | <duration>` : Crée un giveaway (admin).
- `!enter <giveawayId>` : S’inscrire à un giveaway.
- `!raffle <giveawayId>` : Tirer un gagnant (admin).
- `!markhelpful <messageId>` : Marquer un message comme utile (mod).

## Fonctionnalités

- XP automatique pour l’activité en envoyant des messages.
- Points d’aide pour chaque message jugé utile.
- Salon de discussion spécial où le créateur peut noter les réponses comme utiles.
- Conversion XP + help points en tokens pour participer aux giveaways.

## Installation

1. Installer Node.js
2. Cloner ce dépôt
3. `npm install`
4. Ajouter ton token Discord dans `config.json` ou via variable d'environnement
5. `node index.js` pour lancer le bot
