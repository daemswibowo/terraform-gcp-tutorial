# Terraform GCP Tutorial

## Requirements

- [Terraform CLI](https://developer.hashicorp.com/terraform/install)

# Prepare Variables

After cloning this repository, copy the `terraform.tfvars.example` file to `terraform.tfvars`

```bash
cp terraform.tfvars.example terraform.tfvars
```

Then modify it to match your configuration. Don't forget to place your GCP service account credentials JSON file to `credentials/my-credentials.json` or you can name it if you wish.

# Run

```bash
terraform apply
```

# Destroy

```bash
terraform destroy
```