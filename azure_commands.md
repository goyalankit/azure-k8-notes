```
# Create new resource group
az group create --name angoyal-kubernetes -l eastus2

# Create a Vnet
az network vnet create -g angoyal-kubernetes \
  -n angoyal-kubernetes-net \
  --address-prefix 10.240.0.0/24 \
  --subnet-name angoyal-kubernetes-subnet
```
