
## Contexte du projet
Ce projet a pour objectif de développer une **application web interactive** permettant de gérer des offres d’emploi, un profil utilisateur et un système de favoris.  
L’application repose sur **JavaScript Vanilla**, sans frameworks externes, et met l’accent sur la **validation des formulaires**, la **recherche avancée**, la **persistance locale** et une **interface responsive**.



## Fonctionnalités clés

### 1. Validation de formulaires
- **Profil utilisateur** : Validation du nom, email et compétences.  
- **Formulaire d’offre** : Vérification des champs obligatoires (titre, entreprise, description).  
- **Feedback en temps réel** : Messages d’erreur et de succès dynamiques.

### 2. Recherche et filtrage avancé
- **Recherche texte** : Recherche dans les titres, entreprises et descriptions.  
- **Filtres multiples** : Par compétences, type de contrat et localisation.  
- **Filtrage combiné** : Possibilité de combiner recherche et filtres.

### 3. Opérations CRUD complètes
- **Ajout** : Formulaire modal pour créer de nouvelles offres.  
- **Édition** : Modification des offres existantes.  
- **Suppression** : Suppression avec confirmation et mise à jour de l’UI.  
- **Affichage** : Cartes d’offres responsives.

### 4. Système de favoris
- **Ajout/retrait** : Bouton de favori interactif.  
- **Section dédiée** : Onglet "Favoris" pour retrouver les offres enregistrées.  
- **Persistance** : Sauvegarde automatique dans le `localStorage` (bonus).

### 5. Gestion de profil
- **Compétences** : Ajout/suppression dynamique.  
- **Préférences** : Métier recherché et localisation.  
- **Sauvegarde automatique** : Données persistantes localement.

### 6. Gestion d’événements
- **Interactions dynamiques** : clics, favoris, édition, navigation.  
- **Changement d’onglets** : Tous / Favoris / Mes Offres.  
- **Soumission & validation** : Gestion complète des formulaires.

---

## User Stories principales

### Gestion des formulaires
- En tant qu’utilisateur, je veux recevoir des **messages d’erreur clairs** pour des saisies invalides.  
- En tant qu’utilisateur, je veux que le **formulaire empêche l’envoi** de données incomplètes.  

### Recherche et filtrage
- En tant qu’utilisateur, je peux **rechercher des offres** par mots-clés.  
- En tant qu’utilisateur, je peux **filtrer les offres** par compétences ou type de contrat.  
- En tant qu’utilisateur, je veux que les résultats **se mettent à jour en temps réel**.

### Gestion des offres
- Ajouter, modifier ou supprimer mes offres depuis une interface claire.  
- Confirmation avant suppression.  
- Mise à jour automatique de la liste des offres.

### Système de favoris
- En tant qu’utilisateur, je peux **ajouter/retirer** des favoris.  
- En tant qu’utilisateur, je veux **retrouver mes favoris** après redémarrage du navigateur.

### Profil utilisateur
- Je peux **éditer mon profil**, ajouter des compétences, définir mes préférences.  
- Les données sont **sauvegardées automatiquement**.
