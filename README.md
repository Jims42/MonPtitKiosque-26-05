# MonPetitKiosque

## 1. Présentation du projet

**MonPetitKiosque** est une application web destinée aux patients, visiteurs et personnels hospitaliers.

Elle permet d’acheter des **articles non périssables** du kiosque de l’hôpital et de les retirer :

- Au kiosque pendant les heures d’ouverture
- Dans des casiers automatiques accessibles 24h/24 et 7j/7

### Objectifs

- Proposer un catalogue digital d’articles non périssables
- Permettre l’achat en ligne via un parcours simple et sécurisé
- Offrir un retrait autonome via casiers automatiques
- Gérer les stocks en temps réel (kiosque + casiers)
- Fournir un back-office complet pour le personnel
- Assurer une expérience fluide et accessible pour tous les utilisateurs

## 2. Périmètre des produits

L’application propose uniquement des **articles non périssables** :

- Magazines, journaux, livres
- Mots croisés, sudoku
- Produits d’hygiène (savon, gel, mouchoirs…)
- Accessoires (chargeurs, écouteurs, stylos, carnets…)
- Snacks et boissons emballés longue conservation (optionnel)

**Exclus :**

- Produits frais
- Produits réfrigérés
- Produits à date courte

## 3. Fonctionnalités détaillées

### 3.1 Front-office (utilisateurs)

- Page d’accueil MonPetitKiosque
- Catalogue avec catégories, filtres et recherche
- Fiches produits
- Panier et gestion des quantités
- Paiement sécurisé
- Choix du mode de retrait
- Sélection d’un casier libre
- Confirmation de commande
- Envoi automatique du code de retrait
- Suivi de commande
- Espace personnel

### 3.2 Back-office (administration)

- Gestion du catalogue
- Gestion des stocks
- Gestion des commandes et états
- Gestion des casiers
- Statistiques
- Gestion des utilisateurs internes
- Paramétrages généraux

### 3.3 Gestion des casiers automatiques

- Communication via API du fabricant
- Attribution automatique d’un casier libre
- Envoi du code de retrait au client
- Détection de l’ouverture du casier
- Mise à jour automatique de l’état du casier
- Historique des ouvertures et incidents

## 4. Contraintes techniques

### Architecture

- Application web responsive (mobile-first)
- Framework recommandé : Symfony, Laravel, Node.js ou équivalent
- Base de données SQL
- API REST pour les casiers
- Hébergement sécurisé HTTPS

### Sécurité

- Conformité RGPD
- Paiement sécurisé (PCI-DSS)
- Chiffrement des données sensibles
- Gestion des rôles et permissions
- Journalisation des actions critiques

## 5. Design et ergonomie

- Interface simple, rassurante et accessible
- Respect des normes WCAG 2.1 AA
- Couleurs adaptées à l’environnement hospitalier

## 6. Contenus

- Descriptifs produits
- Photos HD
- Mentions légales
- CGV
- Politique de confidentialité
- FAQ
- Support client

## 7. Livrables attendus

- Application complète
- API casiers
- Documentation technique
- Documentation utilisateur
- Formation du personnel
- Jeux de tests
- Mise en production

## 8. Planning prévisionnel

| Phase | Durée estimée |
|---------|---------|
| Analyse & conception | 2 à 4 semaines |
| Développement | 6 à 10 semaines |
| Intégration casiers | 2 à 4 semaines |
| Tests & validation | 2 semaines |
| Mise en ligne | 1 semaine |

## 9. Budget estimatif

Entre **12 000 € et 50 000 €**.

## 10. Évolutions possibles

- Application mobile
- Programme de fidélité
- Notifications push
- Livraison en chambre
- Intégration avec badges du personnel
- Extension à d’autres services hospitaliers
