# Terraform Enterprise: Clustering

## Inputs

| Name | Description | Type | Default | Required |
|------|-------------|:----:|:-----:|:-----:|
| prefix | Prefix for resource names | string | n/a | yes |
| vpc\_id | AWS VPC id to install into | string | n/a | yes |
| allow\_list | list of CIDRs we allow to access the infrastructure | list | `[]` | no |
| subnet\_tags | tags to use to match subnets to use | map | `{}` | no |

