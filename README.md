# terraform-eks
A sample repository to create EKS on AWS using Terraform.

### Install AWS CLI 
![image](https://github.com/rohith200/Terraform/assets/42884535/33f75b9e-0b03-4fca-8b97-696d6689baf6)


As the first step, you need to install AWS CLI as we will use the AWS CLI (`aws configure`) command to connect Terraform with AWS in the next steps.

Follow the below link to Install AWS CLI.
```
https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html
```

### Install Terraform

Next, Install Terraform using the below link.
```
https://developer.hashicorp.com/terraform/tutorials/aws-get-started/install-cli
```
![image](https://github.com/rohith200/Terraform/assets/42884535/95b658a0-5aa6-4a4a-9695-0481064c46c4)

### Connect Terraform with AWS

Its very easy to connect Terraform with AWS. Run `aws configure` command and provide the AWS Security credentials.
![image](https://github.com/rohith200/Terraform/assets/42884535/503fd06c-6796-423d-a66b-99599dc641b3)


### Initialize Terraform

Clone the repository and Run `terraform init`. This will intialize the terraform environment for you and download the modules, providers and other configuration required.

![image](https://github.com/rohith200/Terraform/assets/42884535/08450d39-1d14-4b91-91ed-06864fdaae67)
![image](https://github.com/rohith200/Terraform/assets/42884535/b425ef74-bd8a-4f84-ba3e-43a6ccba0a7d)
![image](https://github.com/rohith200/Terraform/assets/42884535/e0c3aa9d-0376-4f57-89bd-3b3b9298409c)

### Optionally review the terraform configuration

Run `terraform plan` to see the configuration it creates when executed.
![image](https://github.com/rohith200/Terraform/assets/42884535/2fd67a77-01c7-44c9-ac04-19b0529a14fb)
![image](https://github.com/rohith200/Terraform/assets/42884535/d3869ef6-acf9-42b9-9a48-f3eaecb7304f)

### Finally, Apply terraform configuation to create EKS cluster with VPC 

`terraform apply`
![image](https://github.com/rohith200/Terraform/assets/42884535/f963cb4f-a4f4-4bfc-af3f-6e0cda4f43be)
![image](https://github.com/rohith200/Terraform/assets/42884535/ad66bb43-3ff5-4fc7-98cd-745c78ec9eda)

Below images looks in AWS Dashboard
![image](https://github.com/rohith200/Terraform/assets/42884535/43c9af08-3ecb-474e-aa0a-14c451a7a498)
![image](https://github.com/rohith200/Terraform/assets/42884535/d04ae7b7-fe54-4030-8708-ae246f972f7b)
![image](https://github.com/rohith200/Terraform/assets/42884535/a8734537-7e4c-411b-903d-59353114196e)





