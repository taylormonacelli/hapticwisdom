Taking incus terraform provider for a test drive.

```bash

terraform plan -out=tfplan && terraform apply tfplan && incus ls
terraform plan -destroy -out=tfplan && terraform apply tfplan && incus ls
incus shell instance1

```
