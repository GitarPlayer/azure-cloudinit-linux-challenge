# azure-cloudinit-linux-challenge
cloudinit vm that contains setup a partially broken Ubuntu 1804 VM on Azure
# Usage
```bash
az group create --name cloud-init --location eastus
az vm create \
    --resource-group cloud-init \
    --name linuxVM \
    --image UbuntuLTS \
    --admin-username azureuser \
    --generate-ssh-keys \
    --custom-data cloud-init.txt
```
