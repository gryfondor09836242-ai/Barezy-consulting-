# BAREZY CONSULTING — Pack final prêt à déployer

Ce pack prépare la plateforme BAREZY CONSULTING pour une mise en production.

## Ce qui est prévu
- Marketplace produits + services
- Panier et commandes
- Paiement Orange Money
- Paiement Wave
- Vérification serveur des paiements
- Suivi des commandes
- Espace administrateur
- API backend
- Préparation Android

## Important
Les clés API Orange Money et Wave ne doivent jamais être placées dans l'application mobile ou envoyées dans le chat.
Elles seront configurées comme secrets sur le serveur.

## Derniers éléments nécessaires avant la mise en ligne
1. Un hébergement serveur HTTPS.
2. Les identifiants API Orange Money du compte marchand.
3. La clé API Wave Business.
4. Les URLs HTTPS de retour/webhook.

Le numéro marchand Orange Money fourni est : 0712483832.
Il ne remplace pas les identifiants API.

## Architecture
Client → panier → paiement Orange Money / Wave → serveur → confirmation → commande PAYÉE → livraison.
