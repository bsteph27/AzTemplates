# Multi tier VNet with NSGs and DMZ

[![Deploy To Azure](https://raw.githubusercontent.com/bahnhacker/AzTemplates/master/deploytoazure.svg?sanitize=true)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fbahnhacker%2FAzTemplates%2Fmaster%2FVNet-Complete%2Fazuredeploy.json)
[![Deploy To Azure US Gov](https://raw.githubusercontent.com/bahnhacker/AzTemplates/master/deploytoazuregov.svg?sanitize=true)](https://portal.azure.us/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fbahnhacker%2FAzTemplates%2Fmaster%2FVNet-Complete%2Fazuredeploy.json)


Provisions a new virtual network (VNet) and subnets (snet) with network security groups (NSG) assocaited to each subnet. The NSGs define a DMZ for the application subnet to expose endpoints to the internet, securing traffic between the application and database subnets, blocking outbound internet access to VMs in both the application and database subnets, and opening up the database subnet only on port 1433. 

Variables will be defined upon execution and include:
* Azure Region
* Address Prefix for VNet and snets
* VNet Name
* snet Names
* NSG Names


==================================================

Template customized for personal use. Anyone utilizing this script is encouraged to complete thurough review and testing prior to its use. 
The orginal source is available @: https://github.com/Azure/azure-quickstart-templates/tree/master/201-nsg-dmz-in-vnet/
