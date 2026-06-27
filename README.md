# Azure App Service + SQL Database Project

> Web application architecture with managed database on Microsoft Azure | AZ-104 Hands-on Project

## Project Overview
Designed and partially implemented a web application architecture on Microsoft Azure using Azure App Service and Azure SQL Database. Successfully provisioned and configured the Azure SQL Database with secure networking settings. App Service deployment is pending subscription upgrade.

## Azure Services Used
| Service | Purpose | Status |
|---|---|---|
| Azure SQL Database (Basic tier) | Managed relational database | Completed ✅ |
| Azure SQL Server | Database server hosting | Completed ✅ |
| App Service (Free F1) | Web application hosting | Planned ⬜ |
| Application Insights | App monitoring & diagnostics | Planned ⬜ |
| Connection Strings | Secure app-to-database connectivity | Planned ⬜ |

## Architecture
```
User Browser
   |
   v
Azure App Service (Web App)
   |
   v
Connection String (SQLAzure)
   |
   v
Azure SQL Database (Basic tier)
   |
   v
Azure SQL Server (anuserver-db)
```

## What I Completed
1. Created Azure SQL Database (Basic tier, Central India region)
2. Configured SQL Server with Microsoft Entra authentication
3. Set networking to Public endpoint with Azure services access enabled
4. Configured Basic tier (5 DTUs, 2GB storage) for cost efficiency
5. Researched App Service connection string and Application Insights setup

## What I Learned
- Provisioning and configuring Azure SQL Database via Azure Portal
- Understanding DTU-based pricing model (Basic vs Standard vs Premium)
- Configuring SQL Server networking — public vs private endpoints
- Microsoft Entra authentication vs SQL authentication for databases
- How App Service connects to SQL Database via connection strings
- Azure free trial subscription limitations and quota management

## Next Steps
- Deploy App Service (Free F1 tier) after subscription upgrade
- Configure SQLAzure connection string in App Service environment variables
- Enable Application Insights for monitoring
- Deploy sample web application to App Service

## Certification
This project is part of my hands-on preparation for the **Microsoft AZ-104: Azure Administrator Associate** certification (passed 2025).

## Author
Raghupatruni Naga Prasanthi Kumari
Cloud Support Engineer | AZ-104 Certified
- Email: nagaprasanthi13@gmail.com
- LinkedIn: linkedin.com/in/prasanthi-raghupatruni-500503203
