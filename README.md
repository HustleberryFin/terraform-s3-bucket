# Terraform S3 Bucket (AWS)

This project uses [Terraform](https://www.terraform.io/) to provision a secure, versioned AWS S3 bucket.

## 🔧 Features

- Creates an S3 bucket with:
  - Versioning enabled
  - Public access blocked
  - Server-side encryption

## 📁 Files

- `main.tf` – Contains all infrastructure configuration
- `.gitignore` – Excludes Terraform-generated files and sensitive state

## 🚀 How to Use

1. Update your AWS credentials with `aws configure`
2. Run `terraform init` to initialize
3. Run `terraform plan` to preview changes
4. Run `terraform apply` to deploy

## 📌 Notes

- `.terraform/`, `*.tfstate`, and other sensitive files are excluded from version control
- Designed for learning and portfolio development — not intended for production as-is

## 👤 Author

[R.Ian Perez](https://github.com/HustleberryFin)
