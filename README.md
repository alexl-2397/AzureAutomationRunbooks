These are a few Powershell scripts that I've find useful when needing automation within Azure.
Each of these scripts use the Automation Accounts Managed Identity, and so to run these they will need sufficient permissions to the Azure resources.


The Azure Disk Resizer is exactly what it says, it will resize a disk within Azure. A temporary storage account is created when using this, and so it will need permissions to do so.
The Storage Account SFTP Manager allows to you enable or disable SFTP on Gen2 storage accounts. This is good for security, and also FinOps within Azure.
The Virtual Machine Manager allows to you power down and power up virtual machines. This is great for FinOps, and also lowers attack surface if the machine is accessbile publicly.

I haven't found a massive amount of use cases for Azure automation for the Azure environment. This type of Automation is great for Hybrid Workers if you require them - Hybrid Workers are great for onboarding and offboarding users.
