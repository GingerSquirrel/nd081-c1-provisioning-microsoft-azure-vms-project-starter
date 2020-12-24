# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.

*For **both** a VM or App Service solution for the CMS app:*
- *Analyze costs, scalability, availability, and workflow*
- *Choose the appropriate solution (VM or App Service) for deploying the app*
- *Justify your choice*

App service (PaaS) is cheaper than VMs (IaaS), easier to scale, requires less maintainance and easier to configure.

VMs require regular manual updates to the underlying OS whereas the App Service's OS is maintained by Microsoft.

Costs - App Service is cheaper
Scalability - App service is scaled easier as it has a built in load balancer
Availabilty - Both have very high availability.
Workflow - App service has deployment slots, both work with various devops processes.


### Assess app changes that would change your decision.

*Detail how the app and any other needs would have to change for you to change your decision in the last section.* 

If the site grew so large that it exceeds the CPU power and memory that the app service provides it can be moved to a VM.

If the app running on the app service needed to control the underlying OS or have custom software installed for it to run it would have to be
migrated over to a VM.
