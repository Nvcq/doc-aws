# Documentation AWS
Groupe n°6 : Nicolas MOPIN | Simon ROCHE | Armand DORARD | Thomas CARDIET

## Cluster
### Connecion to cluster
```
az account set --subscription 1062deed-79a8-4c9e-9d77-31235d059b7f
```
```
az aks get-credentials --resource-group iim-azure --name iim-azure --overwrite-existing
```
### Create namespace
```
kubectl create namespace <nom>
```
### Connection to namespace
```
kubectl config set-context --current --namespace=<namespace>
```

## Docker
### Clone
```
git clone git@github.com:Azure-Samples/aks-store-demo.git
```
### Compose
```
docker compose -f docker-compose-quickstart.yml up
```
### Connection to registry
```
az acr login --name devtchao
```
### Tag image
```
docker tag rabbitmq:3.11.17-management-alpine devtchao.azurecr.io/<trigramme>-rabbitmq
```
### Push image
```
docker push devtchao.azurecr.io/<trigramme>-rabbitmq
```




```

```
