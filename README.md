# Introduction 
This is the baseline repo for Azure Synapse Analytics that enables the creation of:
- Resource Group
- Azure Key Vault
- Azure ADLS Gen 2 Storage Account
- Azure Synapse Workspace
- Azure Synapse Dedicated Pool (Gen2) - ToDo
- Azure Synapse Spark Pool - ToDo


# Getting Started
TODO

# Build and Test
TODO

The template artefacts are all based on the Azure Resource Manager syntax, and is meant to be deployed in Azure DevOPS

Ensure that in the Parameter file for the Azure Synapse Analytics Workspace ARM code that you override the userObjectId value with a valid ObjectID GUID from your Admin User Group as this will be used to ser RBAC Admin Access to the Filesystem and the Workspace






If you want to learn more about creating good readme files then refer the following [guidelines](https://docs.microsoft.com/en-us/azure/devops/repos/git/create-a-readme?view=azure-devops). You can also seek inspiration from the below readme files:
- [ASP.NET Core](https://github.com/aspnet/Home)
- [Visual Studio Code](https://github.com/Microsoft/vscode)
- [Chakra Core](https://github.com/Microsoft/ChakraCore)