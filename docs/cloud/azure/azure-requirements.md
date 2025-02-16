# Azure Requirements

## Pentest Requirements

* **Global Reader** and **Security Reader** roles in Azure AD
* **Reader** permission over the subscription


## Powershell and Native Modules

* [Microsoft Graph](https://learn.microsoft.com/en-us/powershell/microsoftgraph/installation?view=graph-powershell-1.0): `Install-Module Microsoft.Graph -Scope CurrentUser`
* [Azure AD](https://learn.microsoft.com/fr-fr/powershell/azure/active-directory/install-adv2?view=azureadps-2.0): `Install-Module AzureAD`
* [Azure AD Preview](https://learn.microsoft.com/fr-fr/powershell/azure/active-directory/install-adv2?view=azureadps-2.0): `Install-Module AzureADPreview`
* [Azure CLI](https://learn.microsoft.com/fr-fr/cli/azure/install-azure-cli-windows?tabs=winget): `winget install -e --id Microsoft.AzureCLI`


## Terminology

* **Tenant**: An instance of Azure AD and represents a single organization.
* **Azure AD Directory**: Each tenant has a dedicated Directory. This is used to perform identity and access management functions for resources.
* **Subscriptions**: It is used to pay for services. There can be multiple subscriptions in a Directory.
* **Core Domain**: The initial domain name <tenant>.onmicrosoft.com is the core domain. It is possible to define custom domain names too.



## References

* [Az - Permissions for a Pentest - HackTricks](https://cloud.hacktricks.xyz/pentesting-cloud/azure-security/az-permissions-for-a-pentest)