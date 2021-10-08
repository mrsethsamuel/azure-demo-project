# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

*For **both** a VM or App Service solution for the CMS app:*
- *Analyze costs, scalability, availability, and workflow*
- *Choose the appropriate solution (VM or App Service) for deploying the app*
- *Justify your choice*


--------------------
### Decision

Deployment option: App Service ([https://democapp.azurewebsites.net/](https://democapp.azurewebsites.net/))

--------------------
### Resource Justification

Azure VMs cost more to run than Azure App Service. Azure App Service is less scalable than Azure VMs. So Azure VMs are favored for apps that can grow in the future. Compared to Azure Virtual Machines, Azure App Service requires far less management. Azure App Service makes app development easier and faster. Azure VMs provide developers more power. In Azure App Service, you can't specify the VM's OS. Pay -as-you-go is  Not available in Azure App Service, So you pay for a service plan even if you don't use it. Certain programming languages may not be supported by Azure App Service. In that instance, one must use Azure VM to create a language environment.

--------------------

### Assess app changes that would change your decision.

*Detail how the app and any other needs would have to change for you to change your decision in the last section.*

App Service's are limited 14 GB of Memory and 4 VCPUs. If the application were to be a high compute application the need to extend hardware requirements would call for a Virtual Machine. A need to utilize custom monitoring and logging solutions could also necessitate a shift to VMs. Also if the application has dependencies to specific softwares on a server then a VM would be more suitable.
