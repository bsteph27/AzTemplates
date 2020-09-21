# Policies via Blueprint 

[![Deploy To Azure](https://raw.githubusercontent.com/bahnhacker/AzureTemplates/master/deploytoazure.svg?sanitize=true)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fbahnhacker%2FAzureTemplates%2Fmaster%2FPolicy-Blueprint%2FPolicy-Blueprint.json)
[![Deploy To Azure US Gov](https://raw.githubusercontent.com/bahnhacker/AzureTemplates/master/deploytoazuregov.svg?sanitize=true)](https://portal.azure.us/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fbahnhacker%2FAzureTemplates%2Fmaster%2FPolicy-Blueprint%2FPolicy-Blueprint.json)


Policy Name
* A security contact email address should be provided for your subscription
* A security contact phone number should be provided for your subscription
* Enable Monitoring in Azure Security Center
* Audit usage of custom RBAC rules
* Allowed locations
* MFA should be enabled on accounts with owner permissions on your subscription
* Require a tag on resources (ex. BuildDate)
* Require a tag on resource groups (ex. AppSvc)
* Inherit a tag from the subscription if missing (ex. EnviTier)
* Inherit a tag from the resource group if missing (ex. AppSvc)
* Azure Monitor log profile should collect logs for categories 'write,' 'delete,' and 'action'
* Azure Monitor solution 'Security and Audit' must be deployed
* Azure subscriptions should have a log profile for Activity Log
* Automatic provisioning of the Log Analytics monitoring agent should be enabled on your subscription
* Deploy Diagnostic Settings for Network Security Groups
* Gateway subnets should not be configured with a network security group
* Internet-facing virtual machines should be protected with Network Security Groups
* Non-internet-facing virtual machines should be protected with network security groups
* Subnets should be associated with a Network Security Group
* Allowed storage account SKUs
* Deploy default Microsoft IaaSAntimalware extension for Windows Server
* Microsoft Antimalware for Azure should be configured to automatically update protection signatures
* Microsoft IaaSAntimalware extension should be deployed on Windows servers
* Audit virtual machines without disaster recovery configured
* Audit VMs that do not use managed disks
* Allowed virtual machine size SKUs
* Audit Windows VMs on which the Log Analytics agent is not connected as expected
* Audit Windows VMs that do not match Azure security baseline settings
* Audit Windows VMs with a pending reboot
* Deploy Log Analytics agent for Linux virtual machine scale sets
* Deploy Log Analytics agent for Linux VMs
* Deploy Log Analytics agent for Windows virtual machine scale sets
* Deploy Log Analytics agent for Windows VMs
* Enable Azure Monitor for VMs
* Enable Azure Monitor for Virtual Machine Scale Sets
* Monitor missing Endpoint Protection in Azure Security Center
* System updates on virtual machine scale sets should be installed
* System updates should be installed on your machines
* Disk encryption should be applied on virtual machines

