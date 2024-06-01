# How can help modules terraform-magalu-cloud


## Installing dependences:
The projects use pre-commit, tflint, terraform-docs and terraform (off course). You need install this tools, how:<br>
[How install tflint](https://github.com/terraform-linters/tflint)<br>
[How install terraform-docs](https://terraform-docs.io/user-guide/installation/)<br>
[How install terraform](https://developer.hashicorp.com/terraform/install)<br>
[How install pre-commit](https://pre-commit.com/#install)<br>


## Standards in use
[Best Practices Terraform](https://www.terraform-best-practices.com/)<br>
[Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/)<br>


### Common practices:
- Each module need variable create
- Always that possible, insert validation variables
- Avoid object variable, use any instead object
- Ensure that code example work fine
- Write test and validation 
- Pay attention with count and for, make sure your code does not cause problems to third parties
- Your code need work fine: create, update, delete and avoid input break change.