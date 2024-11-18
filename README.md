# Projet de Gestion de Comptes Bancaires

## Description

Ce projet est une application RESTful développée avec **Spring Boot** pour la gestion de comptes bancaires. Elle permet d'effectuer des opérations CRUD (Créer, Lire, Mettre à jour, Supprimer) sur les comptes. L'application prend en charge les formats **JSON** et **XML** pour les échanges de données et initialise des comptes de test lors du démarrage.

---

## Fonctionnalités

### Endpoints disponibles

1. **Récupérer tous les comptes**
   - **Méthode** : `GET`
   - **URL** : `/banque/comptes`
   - **Format de réponse** : JSON, XML
   - **Description** : Renvoie la liste de tous les comptes.

2. **Récupérer un compte par ID**
   - **Méthode** : `GET`
   - **URL** : `/banque/comptes/{id}`
   - **Format de réponse** : JSON, XML
   - **Description** : Renvoie les détails d'un compte spécifique.

3. **Créer un nouveau compte**
   - **Méthode** : `POST`
   - **URL** : `/banque/comptes`
   - **Format d'entrée** : JSON, XML
   - **Format de réponse** : JSON, XML
   - **Description** : Ajoute un nouveau compte.

4. **Mettre à jour un compte existant**
   - **Méthode** : `PUT`
   - **URL** : `/banque/comptes/{id}`
   - **Format d'entrée** : JSON, XML
   - **Format de réponse** : JSON, XML
   - **Description** : Met à jour les informations d'un compte existant.

5. **Supprimer un compte**
   - **Méthode** : `DELETE`
   - **URL** : `/banque/comptes/{id}`
   - **Description** : Supprime un compte spécifique.

## video

https://github.com/user-attachments/assets/0bcdd8ea-10e8-4079-9ffb-aef796a5540a



https://github.com/user-attachments/assets/f6b5e522-4f2f-42d5-aaf0-cc2e1c5af53e

