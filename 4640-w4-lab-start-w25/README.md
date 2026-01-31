# 4640-w4-lab-start

Sources:
- https://cloudinit.readthedocs.io/en/latest/index.html
- [https://gitlab.com/cit_4640/4640-w4-lab-start-w25](https://gitlab.com/cit_4640/4640-w4-lab-start-w25) 
- https://developer.hashicorp.com/terraform/language/terraform#terraform
- https://registry.terraform.io/providers/hashicorp/aws/latest/docs/data-sources/ami
- https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/vpc
- https://developer.hashicorp.com/terraform/language/block/locals#basic-locals-example
- https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/vpc#enable_dns_hostnames-1
- https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/route_table

## Config commands

## Terraform commands
- ```bash
  terraform init
  terraform validate
  terraform plan
  terraform apply
  ```

if error
```
terraform destroy
```

  
### Cloud init config
```bash
⁨ssh-keygen -t ed25519 -f ~/.ssh/nathan-lab-wk4
ssh -i ~/.ssh/nathan-lab-wk4 web@54.244.58.143
```

