# ftac
Azure Infrastructure for Data Analytics (FinTech Analytics Cloud (FTAC))

###Install az cli on Mac
```
brew update && brew install azure-cli
```

### Login to Azure
`az login`

### Set Subscription
`az account set --subscription "5f2a44e0-a3d1-443e-87ce-077a895d5276"`

### Run Terraform Commands

```
terraform init
terraform plan
terraform apply
```

### Get kubeconfig details 
```
az aks get-credentials --resource-group cdd94c5795a77b49-rg --name prefix-cdd94c5795a77b49-aks

```