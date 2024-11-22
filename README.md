# Terraform
## AWS CLI Installation:
````
sudo apt install unzip -y
curl "https://awscli.amazonaws.com/awscli-exe-linux-x86_64.zip" -o "awscliv2.zip"
unzip awscliv2.zip
sudo ./aws/install
````
````
aws --version
````
## Terraform Installation:Ubuntu
````
wget -O- https://apt.releases.hashicorp.com/gpg | sudo gpg --dearmor -o /usr/share/keyrings/hashicorp-archive-keyring.gpg
echo "deb [signed-by=/usr/share/keyrings/hashicorp-archive-keyring.gpg] https://apt.releases.hashicorp.com $(lsb_release -cs) main" | sudo tee /etc/apt/sources.list.d/hashicorp.list
sudo apt update && sudo apt install terraform
````
````
terraform --version
````
## Configure AWS Credentials
````
aws configure --profile "profile_name"
````
## Export AWS credentials as environment variables:

**export AWS_ACCESS_KEY_ID="your-access-key-id"**
**export AWS_SECRET_ACCESS_KEY="your-secret-access-key"**
**export AWS_DEFAULT_REGION="your-region"**



