# azure-cli-terraform
Azure CLI + terraform

## docker build

```bash
docker build --rm -f dockerfile -t azure-cli-terraform:latest .
```

## docker run with init command example

```bash
docker run -it -e AZURE_CMD='login --service-principal --username YOUR_APP_ID --password YOUR_APP_ID_PASSWORD --tenant YOUR_TENANT_ID' -e TERRAFORM_CMD=init azure-cli-terraform:latest
```
