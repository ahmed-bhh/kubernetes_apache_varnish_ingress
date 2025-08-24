# Projet Apache + Varnish + Ingress

## Done

- Déploiement d’Apache et de Varnish.  
- Création des services : Apache en ClusterIP et Varnish en NodePort pour les tests.  
- Création d’une ConfigMap pour configurer Varnish afin qu’il redirige les requêtes vers Apache.  
- Passage du service Varnish en ClusterIP avant d’ajouter l’Ingress (j’ai testé en le laissant en NodePort, ça fonctionne aussi mais c’est moins sécurisé).  
- Installation et test de l’Ingress, avec un flux fonctionnel : Ingress  => Varnish => Apache  .
