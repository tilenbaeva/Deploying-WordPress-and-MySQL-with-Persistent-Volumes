# KUBERNETES 
Deploying-WordPress-and-MySQL-with-Persistent-Volumes

This repository will create :

MySQL - ReplicaSet
Wordpress - Deployment
Ingress
Before doing that create 2 secrets:

For MySQL
For TLS

Run the files in the following order.

kubectl create -f mysql-deployment.yaml
kubectl create -f wordpress-deployment.yaml

***NOTE*** :)
kubectl create -f ingress.yaml .    --> Do not copy this file, it did not work properly. Contributions needed. 
