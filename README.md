# WooCommerce Abby Sync

Synchronisation légère WooCommerce → Abby pour les workflows comptables français.

WooCommerce Abby Sync permet de synchroniser automatiquement les commandes WooCommerce avec Abby afin de créer des factures brouillon cohérentes avec WooCommerce, la TVA française et les besoins des indépendants, artistes, designers, artisans et petites structures.

---

## Fonctionnalités

- Création automatique des factures brouillon Abby
- Synchronisation des clients WooCommerce
- Support TVA française
- Support multi-taux TVA
- Synchronisation des lignes produits
- Synchronisation des SKU
- Synchronisation des frais de livraison
- Transmission de la méthode de paiement
- Transmission du numéro de commande WooCommerce
- Prévention des doublons
- Architecture légère
- Aucune dépendance Zapier ou Make
- Compatible WooCommerce HPOS
- Interface d’administration intégrée
- Test de connexion Abby intégré

---

## Conçu pour

- Artistes
- Designers
- Freelances
- Entreprises françaises
- Boutiques WooCommerce
- Utilisateurs Abby
- Artisans
- Petites structures
- Activités créatives

---

## Workflow

```text
WooCommerce
→ TVA WooCommerce
→ Commande
→ WooCommerce Abby Sync
→ Facture brouillon Abby
```

WooCommerce reste la source principale pour :

- les produits
- les taxes
- les prix
- le checkout
- la gestion clients
- les commandes

Abby gère :

- la facturation
- la comptabilité
- la conformité française

---

## Taux TVA supportés

Exemples :

| Type TVA | Taux |
|---|---|
| Standard | 20% |
| TVA réduite art | 5.5% |
| Droits d’auteur | 10% |
| Export | 0% |

La TVA est calculée directement par WooCommerce.

---

## Philosophie du plugin

Le plugin suit une logique volontairement simple :

```text
WooCommerce = environnement commercial
Abby = environnement comptable
```

Le plugin agit uniquement comme :

- un pont de synchronisation ;
- une architecture légère ;
- une couche de communication cohérente.

L’objectif est de limiter :

- les dépendances externes ;
- les workflows complexes ;
- les couches inutiles ;
- les risques de doublons.

---

## Pourquoi ce plugin existe

De nombreuses architectures WooCommerce reposent aujourd’hui sur :

- Zapier ;
- Make ;
- webhooks multiples ;
- automatisations externes complexes.

WooCommerce Abby Sync adopte une approche différente :

- plus légère ;
- plus lisible ;
- plus stable ;
- plus cohérente.

Le plugin a été développé autour d’un besoin réel de gestion WooCommerce et comptabilité française.

---

## Prérequis

- WordPress
- WooCommerce
- Compte Abby
- Clé API Abby

---

## Installation

1. Téléverser le ZIP du plugin
2. Activer le plugin
3. Entrer la clé API Abby
4. Configurer les taxes WooCommerce
5. Commencer la synchronisation des commandes

---

## Synchronisation

Le plugin :

- crée les contacts Abby
- crée les factures brouillon Abby
- transmet les lignes produits
- transmet les taux TVA
- transmet les méthodes de paiement
- transmet les numéros de commande WooCommerce
- évite les doublons

---

## Interface d’administration

Le plugin inclut :

- une page d’accueil
- une page réglages
- un champ clé API Abby
- un bouton test connexion Abby
- une documentation rapide intégrée

---

## Documentation

Documentation complète disponible dans le Wiki GitHub :

https://github.com/eimablank/woocommerce-abby-sync/wiki

---

## Abby

WooCommerce Abby Sync a été développé autour des workflows WooCommerce et Abby afin de proposer une architecture légère et cohérente pour la comptabilité française.

Créer un compte Abby :

https://abby.fr/?code=PK-633462-9Q

---

## Page officielle du plugin

https://sandrinegermain.com/produit/woocommerce-abby-sync/

---

## GitHub & philosophie open workflow

Le projet est publié publiquement afin de :

- documenter le développement ;
- favoriser la transparence ;
- permettre l’amélioration continue ;
- proposer une architecture compréhensible.

GitHub :

https://github.com/eimablank/woocommerce-abby-sync

---

## Développement assisté par IA

Le plugin a été développé dans une logique hybride mêlant :

- architecture système ;
- workflows ;
- WooCommerce ;
- design ;
- développement WordPress ;
- intelligence artificielle comme outil d’assistance.

L’IA permet :

- prototypage rapide ;
- expérimentation ;
- structuration ;
- correction ;
- apprentissage accéléré.

Mais :

- la logique métier ;
- les workflows ;
- les choix d’architecture ;

restent humains.

---

## Roadmap

### V1.0.0

- Synchronisation WooCommerce → Abby
- Factures brouillon
- TVA WooCommerce
- Prévention doublons
- Compatibilité HPOS
- Interface administration
- Test connexion Abby

### V1.1.0

- Logs avancés
- Outils resynchronisation
- Diagnostic

### V2.0.0

- Dashboard
- Extensions atelier
- Outils agence
- Workflows créatifs
- Compatibilité facturation électronique France

---

## Licence

Copyright © Sandrine GERMAIN

Tous droits réservés.

---

## Versions commerciales & support

Releases stables, support et services d’installation disponibles sur :

https://sandrinegermain.com

---

## Auteur

Sandrine GERMAIN  
Architecte, designer et développeuse web française explorant les liens entre :

- architecture numérique ;
- workflows ;
- WooCommerce ;
- design système ;
- automatisation légère ;
- développement assisté par IA.

### Site officiel

https://sandrinegermain.com

### GitHub

https://github.com/eimablank
