# Deployment-of-PostgreSQL-
Créer un espace de travail (namespace) nommé projet1 
Créer un déploiement (Deployment) de 2 Pods d’une image postgresql, le statut des pods doit être “Running”.
1.	Créez le namespace "projet1" en utilisant la commande kubectl create namespace :
![image](https://github.com/IhebMansour/Deployment-of-PostgreSQL-/assets/90302745/f4332602-2a03-4caa-be1a-fe11baed8bf9)
![image](https://github.com/IhebMansour/Deployment-of-PostgreSQL-/assets/90302745/88fe3ed2-8f92-4955-8f52-578f20ba07d9)

  
2.	Créez un fichier YAML pour le déploiement PostgreSQL, par exemple "postgres-deployment.yaml", avec le contenu suivant :
![image](https://github.com/IhebMansour/Deployment-of-PostgreSQL-/assets/90302745/bcfdf0c1-927b-4a1e-bac0-6286638cb45e)

 
3.	Appliquez le fichier YAML pour créer le déploiement dans le namespace "projet1" :
![image](https://github.com/IhebMansour/Deployment-of-PostgreSQL-/assets/90302745/50695d04-a61a-4699-9451-06af7dd06b46)

 
Cela créera un déploiement de 2 Pods PostgreSQL dans le namespace "projet1". Les Pods devraient passer à l'état "Running" une fois que Kubernetes les aura planifiés et démarrés. Vous pouvez vérifier l'état des Pods en utilisant la commande suivante :
![image](https://github.com/IhebMansour/Deployment-of-PostgreSQL-/assets/90302745/3def6d01-d870-4381-af1f-ad949ff4f7dd)

