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
# Guidelines
- Google is prohibited
- Please speak out loud your thoughts when working so we can assist you in case of troubles

# ToDo

 - Install a webserver
 - Add a user called penguin and make it expire it on 2022-04-04
 - unmount /please-unmount/
 
