# Helpdesk - Plateforme de gestion de tickets

Bienvenue sur **Helpdesk**, une application web développée par **Balens Matthis** et **Bogala Jan** dans le cadre de notre **BTS SIO SISR**.  
Ce projet a été conçu pour simplifier la gestion d'incidents en entreprise et offrir une interface claire aux techniciens comme aux utilisateurs.

**Objectif :** permettre aux entreprises de centraliser, suivre et traiter efficacement les demandes techniques.

---

## Aperçu du projet

Helpdesk est une plateforme complète de gestion de tickets avec un système de rôles : utilisateurs classiques, techniciens et administrateurs.  
Le site est entièrement libre et personnalisable, adaptable à tous types d’environnements informatiques.

![image](https://github.com/user-attachments/assets/8429ab56-2c9a-4752-ae64-c3531bd2c576)

---

## Fonctionnalités principales

### Côté utilisateur
- Création de tickets (titre, description, catégorie, système d'exploitation concerné)
- Suivi de l’évolution des tickets
- Modification possible tant que le ticket est en attente
- Changement de mot de passe
- Connexion sécurisée avec vérification active

**Exemple d’écran :**

![image](https://github.com/user-attachments/assets/008f6251-f14c-4382-8896-9163cb3d99e2)
![image](https://github.com/user-attachments/assets/be436225-14db-445d-8432-39f0e06a54d7)
![image](https://github.com/user-attachments/assets/ad63fb6c-4ea2-4bc3-a489-7d50cae9af6a)

---

### Côté technicien / administrateur

- Tableau de bord dynamique avec statistiques globales et mode sombre  

**Exemple d’écran :**

![image](https://github.com/user-attachments/assets/0c485152-df2e-481a-a976-47f72685d023)

- Gestion avancée des tickets :
  - Priorisation (basse, moyenne, élevée, critique)
  - Suivi de l’état de traitement
  - Filtres dynamiques pour trier les tickets
  - Consultation détaillée des tickets  

**Exemple d’écran :**

![image](https://github.com/user-attachments/assets/83daaf61-1ca2-4781-8aec-9e18df747b96)

- Gestion des comptes utilisateurs :
  - Ajout et suppression via formulaire
  - Recherche en temps réel par nom de famille
  - Consultation détaillée des informations utilisateurs (nom, prénom, login, mot de passe MD5)

**Exemple d’écran :**

![image](https://github.com/user-attachments/assets/5e0a78f7-0684-42ba-b0e3-3655b4319eea)

- Gestion des administrateurs :
  - Ajout et suppression avec validation d’identité en cas d’inactivité
  - Consultation des informations administrateurs (nom, prénom, identifiant)

**Exemple d’écran :**

![image](https://github.com/user-attachments/assets/7173c2d3-47bd-4a3d-b591-798103d8d2df)

- Gestion des services :
  - Ajout et suppression via formulaire sécurisé
  - Consultation des services existants (ID et nom)

**Exemple d’écran :**

![image](https://github.com/user-attachments/assets/9e7e4782-5562-4431-9a83-3ee8ef769f19)

- Historique et logs :
  - Consultation de l’historique des actions avec recherche par date

**Exemple d’écran :**

![image](https://github.com/user-attachments/assets/b23ba27a-004b-431a-8f59-a9f7005cb0d5)

---

## Répartition des tâches et implication

Au démarrage du projet, j’ai pris en charge la création d’une première version du panneau d’administration afin de structurer la gestion des tickets, des utilisateurs et des services.  
Cette partie a ensuite été reprise par un camarade pour assurer une meilleure répartition des tâches et optimiser l’avancement du projet.  

Je suis resté pleinement impliqué tout au long du développement en participant aux validations techniques et aux décisions de conception, tout en poursuivant en parallèle un autre projet avec **Jan Bogala**.

---

## Installation

1. Clonez le dépôt  
2. Rendez le script `install.sh` exécutable  
3. Lancez-le pour :
   - Injecter la base de données
   - Configurer les droits nécessaires

```bash
chmod +x install.sh
./install.sh
