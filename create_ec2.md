# Create ec2 instances on AWS using Terraform

![terraform](images/terraform.png)

1) Create environment variables 
   1) *aws_access_key_id*
   2) *aws_secret_key_id*
2) Create a folder for *terraform*
3) Create *main.tf*

4) Preview the actions terraform would take; also can check if there's any errors
   ```
   terraform plan
   ```

5) Execute the plan
   ```
   terraform apply
   ```

6) Destroy everything in the main.tf (can comment out what not needed to be destroyed)
   ```
   terraform destroy
   ```