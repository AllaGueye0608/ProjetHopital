# ProjetHopital

## Description
ProjetHopital est une application basée sur une architecture de microservices pour la gestion d'un hôpital. Ce projet vise à offrir une solution efficace et modulaire permettant la gestion des patients, du personnel médical, des rendez-vous, des dossiers médicaux et de la facturation.

## Architecture
L'application est composée de plusieurs microservices indépendants qui communiquent entre eux via des API REST. Chaque microservice est responsable d'une fonctionnalité spécifique de l'hôpital.

## Microservices

### 1. **Service Gestion des Patients**
   - Gestion des patients (création, mise à jour, suppression)
   - Consultation des informations médicales d'un patient
   - Historique des visites

### 2. **Service Gestion des Médecins et Consultations**
   - Gestion des médecins et du personnel soignant
   - Spécialités et disponibilité des médecins
   - Attribution et gestion des consultations

### 3. **Service Gestion de l’Hôpital**
   - Administration de l'hôpital
   - Gestion des infrastructures et équipements
   - Coordination des services hospitaliers

### 4. **Système de Sécurité et Confidentialité**
   - Gestion des utilisateurs et des rôles
   - Sécurisation des accès via JWT
   - Protection et confidentialité des données médicales

## Technologies Utilisées
- **Backend** : Spring Boot (avec Spring Cloud pour la gestion des microservices)
- **Base de données** : MySQL / PostgreSQL
- **Communication entre services** : API REST, OpenFeign, Eureka (Service Discovery)
- **Sécurité** : Spring Security avec JWT
- **Frontend** : Angular
- **Outils DevOps** : Docker, Kubernetes (pour le déploiement), GitHub Actions

## Installation et Exécution
1. Cloner le projet :
   ```sh
   git clone https://github.com/VotreRepo/ProjetHopital.git
   ```
2. Démarrer les microservices avec Docker Compose :
   ```sh
   docker-compose up --build
   ```
3. Accéder aux différents services via leurs endpoints API.

## Contributeurs
- Alla Gueye
- Awa Faye
- Mame Diadji Wade
- Coumba Gaye
