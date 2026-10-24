
# Commandes du projet Kubernetes

## Vérifier les nœuds
kubectl get nodes

## Déployer l'application Nginx
kubectl apply -f deployment.yaml

## Vérifier le déploiement
kubectl get deployments

## Vérifier les Pods
kubectl get pods

## Créer le Service
kubectl apply -f service.yaml

## Vérifier les Services
kubectl get services
kubectl describe service nginx-service

## Consulter les détails d'un Pod
kubectl describe pod NOM_DU_POD

## Consulter les logs d'un Pod
kubectl logs NOM_DU_POD
