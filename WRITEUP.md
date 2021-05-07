# Write-up Template

### Analyze, choose, and justify the appropriate resource option for deploying the app.
## I choose Azure App Services because,
- Has more availability zones
- More easy to manage and is fast to deploy
- More legacy apps support
- Azure Web Apps is a fast and simple way to create web apps using ASP.NET, Java, Node.js or PHP. It also has built-in CI/CD integration and has zero-downtime deployments. Its take away most of the complexity and lets us concentrate more on the application itself.
## Scalability & Availability of Azure App Services
- A major benefit of Azure App Service is the ability to scale your application based on load
- The SLA for Azure App Services guarantee a 99.95% uptime for each regional deployment.

## Using the Azure Pricing Calculator the estimate monthly costs are:
- Web App -> $54.75
- Storage Account -> $21.84
- SQL Database -> $371.06
- Total -> $447.65

## Factors that will lead to a change to Azure Virtual Machines
- Azure Virtual Machines can deploy Windows or Linux VMs in seconds from own VM image or images from the Azure Marketplace, the ability to scale from one to thousands of VM instances in minutes with Azure Virtual Machine Scale Sets.
- If we need a better control over the deployment or the usage of the app might increase it would be better to migrate to Azure Virtual Machines and use Higher Tier SQL database for better access and security 

### The site is avaliable at:
- https://udacitycms.azurewebsites.net/login