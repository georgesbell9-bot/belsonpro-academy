# BELSONPRO ACADEMY — boutique e-commerce V1.5

## Ce qui est inclus
- Boutique responsive
- Catalogue et recherche
- Panier persistant
- Création de compte / connexion
- Base SQLite
- Commandes
- Espace administrateur
- Ajout/suppression de produits
- Import de fichiers PDF côté serveur
- Structure prête à brancher à un vrai prestataire de paiement

## Lancer en local
1. Installer Node.js 18+.
2. Copier `.env.example` vers `.env`.
3. Modifier `SESSION_SECRET`, `ADMIN_EMAIL` et `ADMIN_PASSWORD`.
4. Dans le dossier : `npm install`
5. Puis : `npm start`
6. Ouvrir `http://localhost:3000`

## Important pour une vraie mise en production
Le paiement est volontairement en mode démonstration. Avant de vendre :
- connecter un prestataire de paiement compatible avec ton pays et ton marché (carte/Mobile Money) ;
- utiliser HTTPS ;
- stocker les PDF dans un stockage privé ;
- délivrer des liens de téléchargement temporaires après confirmation du paiement ;
- ajouter sauvegardes, e-mails transactionnels et politique de confidentialité ;
- changer immédiatement les identifiants administrateur par défaut.

Le code est un socle fonctionnel, pas une certification de sécurité ou de conformité.
