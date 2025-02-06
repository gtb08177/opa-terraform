# opa-terraform
Contains open policy agent policies that will evaluate a Terraform plan to ensure that certain policies are adhered to.

## Usage
``` sh 
opa eval data.terraform.analysis.authz -d main.rego -i input.json -f pretty
false
```
