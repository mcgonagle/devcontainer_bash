# devcontainer bash


`az login --use-device-code`

`az aks get-credentials --resource-group myResourceGroup --name myAKSCluster`

`kubectl config set-context --current --namespace=jenkins`


```
kubectl config get-contexts                          # display list of contexts
kubectl config current-context                       # display the current-context
kubectl config use-context my-cluster-name           # set the default context to my-cluster-name`
```
