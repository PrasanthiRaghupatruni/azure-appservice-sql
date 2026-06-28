# Azure Static Web App + SQL Database Project
> Web application deployed on Microsoft Azure with managed database | AZ-104 Hands-on Project

## Live Site
URL: https://zealous-dune-0591eea00.7.azurestaticapps.net

## Project Overview
Deployed a web application on Azure Static Web Apps connected to Azure SQL Database via secure connection strings. Implemented GitHub Actions CI/CD pipeline for automatic deployments. Successfully provisioned and configured Azure SQL Database with secure networking settings and Microsoft Entra authentication.

## Azure Services Used
| Service | Purpose | Status |
|---|---|---|
| Azure Static Web Apps | Web application hosting with global CDN | Completed ✅ |
| Azure SQL Database (Basic tier) | Managed relational database | Completed ✅ |
| Azure SQL Server | Database server hosting | Completed ✅ |
| Connection Strings | Secure app-to-database connectivity | Completed ✅ |
| GitHub Actions CI/CD | Automatic deployment pipeline | Completed ✅ |

## Architecture
```
User Browser
   |
   v
Azure Static Web Apps (Free tier, Global CDN)
   |
   v
GitHub Actions (CI/CD — auto deploys on every push)
   |
   v
Connection String (SQLAzure — secure environment variable)
   |
   v
Azure SQL Database (Basic tier — anuportfolio-db)
   |
   v
Azure SQL Server (anuserver-db — Entra authentication)
```

## What I Completed
1. Created Azure SQL Database (Basic tier, Central India region)
2. Configured SQL Server with Microsoft Entra authentication
3. Set networking to Public endpoint with Azure services access enabled
4. Configured Basic tier (5 DTUs, 2GB storage) for cost efficiency
5. Created Azure Static Web App (Free tier) connected to GitHub repository
6. GitHub Actions CI/CD pipeline auto-configured by Azure for every code push
7. Added SQL connection string as secure environment variable in Static Web App
8. Verified live deployment at Azure-generated URL

## What I Learned
- Provisioning and configuring Azure SQL Database via Azure Portal
- Understanding DTU-based pricing model (Basic vs Standard vs Premium)
- Configuring SQL Server networking — public vs private endpoints
- Microsoft Entra authentication vs SQL authentication for databases
- Deploying web applications using Azure Static Web Apps
- How GitHub Actions CI/CD pipeline works with Azure
- Securely connecting a web app to a database using environment variables
- Azure free trial subscription limitations and quota management

## Certification
This project is part of my hands-on preparation for the **Microsoft AZ-104: Azure Administrator Associate** certification (passed 2025).

## Author
Raghupatruni Naga Prasanthi Kumari
Cloud Support Engineer | AZ-104 Certified
- Email: nagaprasanthi13@gmail.com
- LinkedIn: linkedin.com/in/prasanthi-raghupatruni-500503203
