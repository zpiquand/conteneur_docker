# ExpertGaming

Bienvenue sur **ExpertGaming**, votre site de référence pour l'achat de jeux vidéo ! Ce README vous présente le fonctionnement du site, les différentes fonctionnalités selon le type d'utilisateur, et la gestion des jeux par l'administrateur.

---

## Présentation du site

**ExpertGaming** est une plateforme de vente de jeux vidéo en ligne. Le site propose un large catalogue de jeux que vous pouvez parcourir librement. Selon que vous soyez connecté, simple visiteur ou administrateur, vous disposez de fonctionnalités adaptées à vos besoins.

---

## Fonctionnalités pour les visiteurs (utilisateurs non connectés)

- **Consultation du catalogue** : 
  - Les utilisateurs non connectés peuvent naviguer sur le site et voir la liste complète des jeux disponibles à la vente.
  - Pour chaque jeu, il est possible de consulter les détails comme le nom, la description, la date de sortie, le genre et la plateforme.
- **Aucune action d'achat ou de gestion** n'est possible sans être connecté.

---

## Fonctionnalités pour les utilisateurs connectés

- **Connexion / Inscription** :
  - Les utilisateurs peuvent s'inscrire sur le site ou se connecter à leur compte existant.
- **Ajout au panier** :
  - Une fois connectés, les utilisateurs peuvent ajouter des jeux à leur panier.
- **Achat de jeux** :
  - Les utilisateurs peuvent procéder à l'achat des jeux présents dans leur panier via un système de paiement intégré.
- **Historique des achats** :
  - Les utilisateurs ont accès à l'historique de leurs achats.

---

## Fonctionnalités pour l'administrateur

L'administrateur du site dispose de droits supplémentaires pour gérer le catalogue de jeux :

- **Ajout de jeux** :
  - L'administrateur peut ajouter de nouveaux jeux au catalogue en renseignant toutes les informations nécessaires (nom, description, date de sortie, genre, plateforme, etc.).
- **Modification de jeux** :
  - Il peut modifier les informations d'un jeu existant.
- **Suppression de jeux** :
  - Il peut retirer un ou plusieurs jeux du catalogue.
- **Gestion des utilisateurs** *(optionnel)* :
  - Selon la configuration, l'admin peut aussi gérer les comptes utilisateurs.

---

## Résumé des rôles

| Rôle                | Voir les jeux | Ajouter au panier | Acheter des jeux | Ajouter/Modifier/Supprimer un jeu |
|---------------------|:-------------:|:-----------------:|:----------------:|:----------------------------------:|
| Visiteur            |      ✅       |        ❌         |        ❌        |               ❌                   |
| Utilisateur connecté|      ✅       |        ✅         |        ✅        |               ❌                   |
| Administrateur      |      ✅       |        ✅         |        ✅        |               ✅                   |

---

## Technologies utilisées

- PHP pour la logique côté serveur
- MySQL pour la base de données
- HTML/CSS/
