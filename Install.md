# Créer une Unité d'Organisation et un Groupe d'Utilisateurs

## Étapes

### 1. Créer une Unité d'Organisation
1. Ouvre l'outil **Utilisateurs et ordinateurs Active Directory**.
2. Clique droit sur ton domaine **wilders.lan**.
3. Sélectionne **Nouveau** > **Unité d'Organisation**.
4. Nom de l'UO : **Wilders_students**.
5. Clique sur **OK**.

### 2. Créer un Groupe d'Utilisateurs
1. Navigue vers l'UO **Wilders_students** que tu viens de créer.
2. Clique droit sur **Wilders_students**.
3. Sélectionne **Nouveau** > **Groupe**.
4. Nom du groupe : **Students**.
5. Type de groupe : **Sécurité**.
6. Portée du groupe : **Global**.
7. Clique sur **OK**.

### 3. Créer un Utilisateur dans le Groupe
1. Clique droit sur l'UO **Wilders_students**.
2. Sélectionne **Nouveau** > **Utilisateur**.
3. Renseigne les informations :
   - **Prénom** : Wilder
   - **Nom** : School
   - **Nom de connexion** : wilder.school
4. Clique sur **Suivant**.
5. Définis un mot de passe et configure les options.
6. Clique sur **Terminer**.
7. Ajoute l'utilisateur au groupe **Students** :
   - Clique droit sur l'utilisateur **Wilder School**.
   - Sélectionne **Propriétés** > **Membre de** > **Ajouter**.
   - Entre **Students**, puis clique sur **OK**.

## Vérification
- Assure-toi que :
  - L'UO **Wilders_students** existe.
  - Le groupe **Students** est bien dans cette UO.
  - L'utilisateur **Wilder School** appartient au groupe **Students**.
