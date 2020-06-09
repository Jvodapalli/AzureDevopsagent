# Introduction 
TODO: Give a short introduction of your project. Let this section explain the objectives or the motivation behind this project. 

# Getting Started
az acr login 
az acr login --subscription 0c09f5d2-8be3-4c51-a901-fb84f24cb7c3 --resource-group ine1k8-rgp-037 --name ine1dvidk8

az aks get-credentials --subscription 0c09f5d2-8be3-4c51-a901-fb84f24cb7c3 --resource-group ine1k8-rgp-037 --name ine1dv-idk8-011

docker run -it ine1dvidk8.azurecr.io/accelq/agent:latest 

kubectl -apply .\k8s-accelqagent.yaml -n accelq 