# azure-cli-terraform
Azure CLI + terraform

## docker build

```bash
docker build --rm -f dockerfile -t azure-cli-terraform:latest .
```

## docker run with init command example

```bash
docker run -it -e CMD=init azure-cli-terraform:latest
```
