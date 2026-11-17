# Prestago pour Claude

Prestago est l'application de planning des intervenants à domicile : aides à domicile, assistantes de vie, femmes de ménage, jardiniers, payés en CESU ou auto-entrepreneurs. Ce plugin connecte Claude à votre propre compte Prestago.

## Ce que vous pouvez faire

- Consulter vos prochains rendez-vous, l'agenda de la semaine et vos heures planifiées.
- Obtenir un bilan d'activité ou financier du mois ou de l'année.
- Rechercher, créer, modifier ou désactiver une fiche client.
- Créer un rendez-vous ponctuel ou récurrent, le déplacer, l'annuler, ou modifier une série.
- Déclarer des congés et gérer vos indisponibilités.
- Trouver un créneau libre.
- Obtenir un PDF : facture client, planning du mois, récapitulatif des heures.

Chaque création, modification ou suppression est récapitulée puis confirmée avant d'être enregistrée.

## Utilisation

1. Installez le plugin, puis connectez Prestago : la page de connexion Prestago s'ouvre. Saisissez votre e-mail et votre mot de passe Prestago, puis cliquez sur **Autoriser**. Décochez « Créer et modifier » pour un accès en lecture seule.
2. Posez vos questions en français, par exemple :
   - « Quels sont mes prochains rendez-vous ? »
   - « Affiche mon planning de la semaine »
   - « Ajoute un rendez-vous avec Marie Dupont samedi de 14h à 15h30 »

Un compte Prestago est nécessaire : https://prestago-app.fr/

Documentation complète (connexion, droits, révocation, dépannage) : https://prestago-app.fr/assistants-ia/

## Données envoyées

Le plugin n'utilise qu'un serveur : `https://api.prestago-app.fr/mcp`, exploité par Prestago. Claude y envoie uniquement les paramètres des outils appelés (dates, noms de clients recherchés, horaires…). Le serveur renvoie les données de votre compte nécessaires à la réponse. L'accès passe par OAuth 2.1 : Claude ne voit jamais votre mot de passe. Vous pouvez révoquer l'accès à tout moment.

- Confidentialité : https://prestago-app.fr/vie-privee/
- Conditions d'utilisation : https://prestago-app.fr/conditions-generales-utilisation/
- Support : https://prestago-app.fr/contact/

## Limites

Les heures affichées sont des heures planifiées. Les montants sont calculés à partir des tarifs, pas des encaissements. Le changement de tarif d'un client, la sous-traitance, les déclarations CESU et le module Agence restent dans l'application Prestago. Service en français, pour la France.
