RES.Automation.Intune.onAzure
Scripts and buildingblocks for ROA integration with Microsoft Intune on Azure

Please first run the prepare-intune-management.ps1 script before using the other scripts in ROA.
This script wil install the necessary prereqs like the AzureAD or AzureADPreview module, create the encrypted Password file and set the required powershell rights in Azure.

!intune-automation-template.ps1
This is the template to be used in scripts with ROA.
De template has the default authentication as function to get a token for the rest of the functions.
