# Lab-7-8-Omar-El-Alami-El-Fellousse-Yassir-Mousmahi-Clement-DALBERTO

## Lab 7

Au cours de ce laboratoire, nous avons abordé les notions clés liées à l’utilisation de Docker et mis en pratique ses principales fonctionnalités.Concrètement, nous avons :

- conçu un Dockerfile permettant de générer une image à partir d’une application Node.js basique,  
- exécuté un conteneur sur notre machine locale et vérifié son accessibilité via le navigateur,  
- déployé plusieurs conteneurs à l’aide de Docker Compose pour en assurer la coordination,  
- et mis en place des environnements applicatifs isolés et facilement reproductibles.

---

## Lab 8

L’objectif de ce laboratoire était de déployer et gérer une application composée de plusieurs pods sur un cluster Kubernetes local à l’aide de Minikube.Nous avons :

- conçu et appliqué les fichiers deployment.yaml et service.yaml pour déployer l’application et la rendre accessible grâce à un service NodePort,  
- effectué une mise à jour de l’image Docker afin d’analyser le déroulement du rollout puis du rollback,  
- vérifié le load balancing entre trois réplicas en actualisant plusieurs fois la page du navigateur,  
- et terminé par le nettoyage du cluster avant l’arrêt de Minikube.