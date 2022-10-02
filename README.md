# packer-proxmox-template
Packer Image Build Template Code For Proxmox

### Validate code & Run Packer Build
```
packer validate -var-file=credentials.pkr.hcl ubuntu-server-focal-docker.pkr.hcl
```
```
packer build -var-file=credentials.pkr.hcl ubuntu-server-focal-docker.pkr.hcl
```