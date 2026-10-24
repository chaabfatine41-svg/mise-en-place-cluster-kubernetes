# mise-en-place-cluster-kubernetes
Déploiement d’un cluster Kubernetes composé d’un nœud Master et de trois Workers pour orchestrer une application Nginx.
## Objectifs du projet

- Mettre en place un cluster Kubernetes.
- Configurer un nœud Master et trois nœuds Workers.
- Déployer une application Nginx.
- Vérifier l'état des nœuds, des Pods et des Services.

## Technologies utilisées

- Kubernetes
- Docker
- kubeadm
- kubectl
- Nginx
- Ubuntu
- VirtualBox

## Fichiers du projet

- `deployment.yaml` : configuration du déploiement Nginx.
- `service.yaml` : configuration du Service pour accéder à Nginx.
- `commandes.md` : commandes Kubernetes utilisées dans le projet.
- ## Architecture du cluster

- **1 nœud Master** : gestion du cluster Kubernetes.
- **3 nœuds Workers** : exécution des applications conteneurisées.
- **Application** : Nginx, déployée avec 3 réplicas.
- **Accès** : Service de type NodePort sur le port `30080`.

## État du projet

Ce dépôt contient les fichiers de configuration et la documentation du projet. Le déploiement réel du cluster reste à réaliser et à tester.
