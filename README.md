# Documentation AWS
Groupe n°6 : Nicolas MOPIN | Simon ROCHE | Armand DORARD | Thomas CARDIET

## Connecion to cluster
```
az account set --subscription 1062deed-79a8-4c9e-9d77-31235d059b7f
```
```
az aks get-credentials --resource-group iim-azure --name iim-azure --overwrite-existing
```
## Create namespace
```
kubectl create namespace <nom>
```
## Connection to namespace
```
kubectl config set-context --current --namespace=<namespace>
```
```

```
