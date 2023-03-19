## Manage DNS AAAA Records in AD DNS using the KopiCloud AD API Terraform Provider
[![Terraform](https://img.shields.io/badge/terraform-v1.3+-blue.svg)](https://www.terraform.io/downloads.html)
[![KopiCloud-AD](https://img.shields.io/badge/kopiCloud_ad-v1.0+-blueviolet.svg)](https://www.kopicloud-ad-api.com)

## Code creates:

- Create DNS AAAA Records
- List ALL DNS AAAA Records
- List DNS AAAA Records filtered by Zone Name
- List DNS AAAA Records filtered by Hostname
- List DNS AAAA Records filtered by Alias

## How to use this code:

- Generate an authentication token in the KopiCloud AD API portal
- Update the file **terraform.tfvars** to adjust the authentication to your environment

## How to deploy the code:

1. Clone the repo
2. Update variables to your environment
3. Execute "**terraform init**"
4. Execute "**terraform apply**"

## References:

- **KopiCloud AD API** available at https://www.kopicloud-ad-api.com
- **KopiCloud AD API Documentation** available at https://help.kopicloud-ad-api.com
- **KopiCloud AD API Terraform Registry** at https://registry.terraform.io/providers/KopiCloud-AD-API/ad/latest
