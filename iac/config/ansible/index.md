# ⚙️ Infrastructure as Code – Projet Cyna

Ce dossier contient les fichiers liés à l'automatisation de l'infrastructure du projet à l’aide de **Terraform** et **Ansible**.

---

## 🌍 Terraform

Les fichiers Terraform permettent de déployer les composants suivants :
- Réseau (VPC, sous-réseaux, routeurs)
- Sécurité (Firewall Fortinet, VPN)
- Instances (EC2 ou VMs dans VMware)
- Stockage (S3, volumes EBS, sauvegardes)

### Commandes de base :

```bash
terraform init
terraform validate
terraform plan
terraform apply
terraform destroy
