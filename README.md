```bash

terraform plan -out=tfplan && terraform apply tfplan && incus ls
terraform plan -destroy -out=tfplan && terraform apply tfplan && incus ls
incus shell instance1

```
