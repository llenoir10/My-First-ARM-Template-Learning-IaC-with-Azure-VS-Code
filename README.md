# My-First-ARM-Template-Learning-IaC-with-Azure-VS-Code
## What I Did 

I followed the [Microsoft Quickstart](https://learn.microsoft.com/en-us/azure/azure-resource-manager/templates/quickstart-create-templates-use-visual-studio-code?tabs=CLI) to learn how to author, validate, and deploy ARM templates using Visual Studio Code and Azure CLI.

What’s in This Repo
- `azuredeploy.json` – Basic ARM template to deploy a storage account
- `azuredeploy.parameters.json` – Parameters file with user-defined input

## Highlights of my Learning
- How to Use VS Code's ARM snippets to build templates quickly
- Live Validation with Intellisense
- Parameterization for reusable deployments
- Deploying real resources with the Azure CLI

## Resources
- [Microsoft Quickstart Guide](https://learn.microsoft.com/en-us/azure/azure-resource-manager/templates/quickstart-create-templates-use-visual-studio-code?tabs=CLI)
- [Azure Arm Template Docs](https://learn.microsoft.com/en-us/azure/azure-resource-manager/templates/overview)

## Screenshots

<br />
Successful deployment of template:  <br/>
<img src="https://i.imgur.com/x5RS6KD.jpeg" height="80%" width="80%" 
<br />

<br />
Error: Invalid SKU <br/>
<img src="https://i.imgur.com/oeF93te.jpeg" height="80%" width="80%" 

Notice premium_LRS was entered alongside F1 as the selected tier. 
<br />
<br />
Error: Must create unique storage name:  <br/>
<img src="https://i.imgur.com/AM9NJia.jpeg" height="80%" width="80%" 
<br />
