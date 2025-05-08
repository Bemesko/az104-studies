---
source: https://microsoftlearning.github.io/AZ-104-MicrosoftAzureAdministrator/Instructions/Labs/LAB_02b-Manage_Governance_via_Azure_Policy.html
---

## What I Did
(All via the portal)
- Created a resource group with some tags assigned to it.
- Used a builtin policy to require all resources in that RG to have my specific tag with that specific value
- Used another builtin policy that automatically assigns the resource group's tag to all its resources (Could be used in combination)

## Next Steps
- Replicate this setup with Bicep
- Learn about Azure Policy enforcement patterns (remediation, validation errors, when to use each)
