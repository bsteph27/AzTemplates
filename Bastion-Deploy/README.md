# Deploy Azure Bastion

[![Deploy To Azure](https://raw.githubusercontent.com/bahnhacker/AzureTemplates/master/deploytoazure.svg?sanitize=true)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fbahnhacker%2FAzureTemplates%2Fmaster%2FBastion-Deploy%2Fazuredeploy.json)
[![Deploy To Azure US Gov](https://raw.githubusercontent.com/bahnhacker/AzureTemplates/master/deploytoazuregov.svg?sanitize=true)](https://portal.azure.us/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fbahnhacker%2FAzureTemplates%2Fmaster%2FBastion-Deploy%2Fazuredeploy.json)
[![Visualize](https://raw.githubusercontent.com/Azure/azure-quickstart-templates/master/1-CONTRIBUTION-GUIDE/images/visualizebutton.svg?sanitize=true)](http://armviz.io/#/?load=https%3A%2F%2Fraw.githubusercontent.com%2FAzure%2FAzureTemplates%2Fmaster%2FBastion-Deploy%2Fazuredeploy.json)


This template will deploy Azure Bastion in a new or existing Azure Virtual Network, along with dependent resources such as the AzureBastionSubnet, Public Ip Address for Azure Bastion, and Network Security Group rules.

ALL resources will be deployed within the SAME Resource Group and Azure Region. A new Virtual Network is only created if 'new' is selected.


==================================================

Template customized for personal use. Anyone utilizing this script is encouraged to complete thurough review and testing prior to its use. 
The orginal source is available @: https://github.com/Azure/azure-quickstart-templates/tree/master/101-azure-bastion
