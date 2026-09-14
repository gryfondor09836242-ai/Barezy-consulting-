# Déploiement BAREZY CONSULTING

### Étape 1 — serveur
Installer Node.js LTS et déployer le backend.

### Étape 2 — HTTPS
Configurer un domaine et un certificat HTTPS.

### Étape 3 — secrets
Ajouter les variables de `.env.example` dans le gestionnaire de secrets de l'hébergeur.

### Étape 4 — paiements
Configurer Orange Money Web Payment et Wave Business Checkout avec les identifiants fournis dans les portails officiels.

### Étape 5 — tests
Tester :
- paiement réussi
- paiement refusé
- annulation
- webhook
- double notification
- commande non payée

### Étape 6 — Android
Pointer l'application vers l'URL HTTPS de l'API, générer un AAB signé et publier sur Google Play.
