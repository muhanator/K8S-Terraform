# K8S-Terraform

## terraform init -backend-config="storage_account_name=<YourAzureStorageAccountName>" -backend-config="container_name=tfstate" -backend-config="access_key=<YourStorageAccountAccessKey>" -backend-config="key=codelab.microsoft.tfstate"

## export TF_VAR_client_id=<service-principal-appid>

## export TF_VAR_client_secret=<service-principal-password>

## terraform plan -out out.plan

## terraform apply out.plan
