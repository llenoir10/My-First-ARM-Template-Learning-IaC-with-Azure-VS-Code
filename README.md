# My-First-ARM-Template-Learning-IaC-with-Azure-VS-Code
What I Did I followed the [Microsoft Quickstart](https://learn.microsoft.com/en-us/azure/azure-resource-manager/templates/quickstart-create-templates-use-visual-studio-code?tabs=CLI) to learn how to author, validate, and deploy ARM templates using Visual Studio Code and Azure CLI.

hat’s in This Repo
- `azuredeploy.json` – Basic ARM template to deploy a storage account
- `azuredeploy.parameters.json` – Parameters file with user-defined input
- `screenshots/` – Visuals of template validation, snippet usage, and CLI output

## 🧪 How to Use
1. Clone this repo
2. Edit the parameter file with your preferred values
3. Run the following in your terminal (make sure Azure CLI is installed and you're logged in):

```bash
az group create --name arm-vscode --location eastus
az deployment group create \
  --resource-group arm-vscode \
  --template-file azuredeploy.json \
  --parameters azuredeploy.parameters.json
