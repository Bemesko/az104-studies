---
source: https://microsoftlearning.github.io/AZ-104-MicrosoftAzureAdministrator/Instructions/Labs/LAB_02a_Manage_Subscriptions_and_RBAC_Entra.html
---

## What I Did
(All via the Portal)
- Accessed my Entra ID permissions and elevated my access (got the User Access Administrator Role and a lot of warnings in the Azure Portal)
- Created a new Management Group
- Moved my subscription to this Management Group
- Assigned the Virtual Machine Contributor permissions to a Security group at the Management Group level
- Created a custom role for Helpdesk that can open support requests except to add new resource providers

## Next Steps

- How could I do these tasks using the Azure CLI/Powershell/Bicep?
  - Creating an MG
  - Moving subscriptions to an MG
  - Assigning permissions at a particular scope
  - Creating custom roles
