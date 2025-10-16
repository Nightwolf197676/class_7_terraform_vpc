Class 7 VPC Creation Homework redone in Terraform!!
To reproduce just copy and paste into vs code and save as vpc.tv
Then run the following:
curl -O --ssl-no-revoke https://raw.githubusercontent.com/aaron-dm-mcdonald/aws-image-resizer/refs/heads/main/.gitignore
save it
run terraform init
terraform plan
terraform fmt
terraform apply to launch it and wait for it to build.

After it is built to tear everything down its just 1 command:
terraform destroy
