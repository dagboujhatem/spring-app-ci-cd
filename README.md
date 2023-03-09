
### Contexte :
Vous travaillez sur un projet de développement d'une application web pour une entreprise fictive. L'équipe de développement utilise GitLab pour le contrôle de version, la collaboration et l'intégration continue. En tant que DevOps, vous devez vous assurer que les processus de développement et de déploiement fonctionnent correctement.

### Objectifs :

Vérifier que l'application peut être compilée et exécutée correctement.
Tester les fonctionnalités de base de l'application pour s'assurer qu'elles fonctionnent correctement.
Vérifier que le déploiement de l'application sur un Cluster K8S de test se déroule sans erreur.

### Étapes :


1. Configurer un environnement de test local :

- [ ] Clonez le dépôt GitLab contenant l'application.
- [ ] Vérifiez que les dépendances de l'application sont correctement installées.
- [ ] Compilez l'application.
- [ ] Exécutez l’appel HTTP localhost:8080/ vérifier que le mesasge suivante s'affiche correctement: "Spring is here!".

2. Configurer l'intégration continue :

- [ ] Créér le fichier DockerFile compatible avec la version Java de l'application
- [ ] Créér le fichier deployement.yml afin de préparer le déploiement dur un cluster K8S
- [ ] Créer puis Configurez le ficher.gitlab-ci.yml pour exécuter automatiquement les étapes de compilation et de packaging de l'application.
- [ ] Configurez le ficher.gitlab-ci.yml pour déployer automatiquement l'application sur un Cluster K8S de votre choix

3. Tester l'application sur l'environnement de test : Cluster K8S

- [ ] Accédez à l'application sur l'environnement de test pour vérifier que toutes les fonctionnalités de base fonctionnent correctement: 
    --> Exécutez l’appel HTTP CLUSTER_IP:8080/ vérifier que le mesasge suivante s'affiche correctement: "Spring is here!"


### Livrables attendues :

- [ ] Le fichier DockerFile 

- [ ] Le fichier deployement.yml 

- [ ] Le fichier .gitlab-ci.yml

- [ ] URL de l'application déployée sur le Cluster K8S CLUSTER_IP:8080/ 
