# EKS Getting Started Guide Configuration

NOTE: This full configuration utilizes the [Terraform http provider](https://www.terraform.io/docs/providers/http/index.html) to call out to icanhazip.com to determine your local workstation external IP for easily configuring EC2 Security Group access to the Kubernetes servers.
Values are taken for testing purposes but they can be replaced. 

After cloning this repo: <br>
run ``terrafom init``<br>
then run ``terraform plan``<br>
finally run ``terraform apply``
