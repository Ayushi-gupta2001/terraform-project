## Hosting the web application on AWS EC2 server using the terraform with custom VPC:

### Setup required :

- AWS Account
- Terraform install

### Steps :

### Terraform installation
1. Provide the terraform provider , here we are using "aws" provider. For reference , how to use the aws provider check this link 👉 : https://registry.terraform.io/providers/hashicorp/aws/latest/docs

2. You can use this below images as well for more clarity: 
![alt text](image.png)

3. Specify the ami id for your EC2 server using **data source block** which basically give the information using API query

4. ![alt text](image-1.png)

5. https://spacelift.io/blog/terraform-tfvars

6. to remove the file from the staging : run this command *** git rm --cached "file-name"

7. /*** to push the new repo to the git hub run these commands :

    1. git init
    2. git add & git commit -m "commit-message" .
    3. git branch -M main
    4. git remote add origin "link"
    5. git remote --set-upstream origin main or git push -u origin main

    ***/

8. provisioner blocks needs to embeeded into resource block, they can't be define on their own
9. The remote-exec provisioner invokes a script on a remote resource after it is created. 


