# GabonMarket 🇬🇦

Marketplace e-commerce mobile-first destinée exclusivement au Gabon.

## Inclus
- 500 produits de démonstration répartis dans 26 catégories
- Mini-pub dynamique disponible sur chaque produit (500/500)
- Recherche et filtres
- GabonMarket IA locale (recherche par besoin + budget)
- Panier et checkout
- Airtel Money : 076 573 756
- Moov Money : 060 156 160
- Commande WhatsApp préremplie
- Livraison Libreville, Akanda, Owendo et zone configurable
- Dashboard administrateur de démonstration
- Architecture prête pour API de paiement, authentification et base de données

## Lancer localement
```bash
npm install
npm run dev
```

## Déployer gratuitement sur Vercel
Le projet est compatible avec le plan Hobby de Vercel. Importer le dossier dans Vercel et déployer.

```bash
npm install
npm run build
```

Le site est statique côté frontend et n'exige aucune base de données pour la démo.

## Production
Avant ouverture commerciale, remplacer les images de démonstration par les images réellement licenciées/fournies, connecter une base de données sécurisée, l'authentification admin, et les API officielles Airtel Money/Moov Money. Ne pas stocker de secrets dans le frontend.
