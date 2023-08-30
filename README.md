# OpenAI-aks

See [https://aka.ms/openAI-aks](https://aka.ms/openAI-aks)


```sh
az group create --name rg-openai --location westeurope
```

```sh
az aks create --resource-group rg-openai --name aks-openai-lab-101 --generate-ssh-keys
az aks get-credentials --resource-group rg-openai --name aks-openai-lab-101
kubectl get nodes
```

```sh
kubectl apply -f https://raw.githubusercontent.com/Azure-Samples/aks-store-demo/main/aks-store-all-in-one.yaml
```

```sh
kubectl apply -f ai-service.yaml
kubectl get pods
kubectl get service store-admin
kubectl get service store-front
# curl http://4.175.193.254/
```

Then follow [https://aka.ms/secure-aoai-aks-lab](https://aka.ms/secure-aoai-aks-lab)
```sh

```

```sh

```