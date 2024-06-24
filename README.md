<div style="text-align: center;">
  <h1> 2 Tier Azure Architecture Diagram</h1>
  <img src="https://ositauche.com/2TierAzureArchitecture.jpg" alt="2 Tier Azure Architecture" style="max-width: 100%; height: auto;">
</div>
<div style="text-align: center;">
  <h1>Project Description</h1>
In this project we would look at how to use a 2 tier azure infrastructure to deploy a highly resilient, scaleable and high availability web app. To achieve this we would be using the following azure resources: Azure DNS, Application Gateway, App Service Plan, Azure SQL Database, Azure Virtual Network Service Endpoint, Azure Monitor, Log Analytics, Azure Devops for CICD.
</div>

<div style="text-align: center;">
  <h1>Prerequisites</h1>
    <ol>
  <li>Azure Account</li>
  <li>Terraform</li>
  <li>Visual Studio Code</li>
  <li>Azure CLI</li>
  <li>Azure Service Principal</li>
  <li>Git</li>
  <li>Azure DevOps</li>
</ol>

  </div>

<h2>The Following are the components in the above architecture:</h2>

<ul>
  <li>
    <strong>Resource Group</strong><br>
    It is the deployment and management service in Azure. It acts as the logical container for Azure resources.
  </li>
  <li>
    <strong>App Service App</strong><br>
    It is a fully-managed platform for deploying and creating cloud applications.
  </li>
  <li>
    <strong>App Service Plan</strong><br>
    It defines the collection of compute resources for a web app to run.
  </li>
  <li>
    <strong>IP Address</strong><br>
    The app service app has a domain name and a public IP address. The domain name is the subdomain name of azurewebsites.net for example azurewebsites.net.
  </li>
  <li>
    <strong>Azure DNS</strong><br>
    It is a hosting service for DNS domains that provide resolutions using Azure infrastructure. If the domains are hosted in Azure, then one can manage the DNS records using the same credentials, tools, APIs, and billing as other Azure services.
  </li>
  <li>
    <strong>Azure SQL Database</strong><br>
    It is a relational database-as-a-service in the cloud. It shares its code base with the Microsoft SQL server database engine. Depending upon the application requirement, one can also use Azure Database for PostgreSQL or Azure Database for MySQL. These are based on Postgres database and open-source MySQL respectively, which are fully managed database services.
  </li>
  <li>
    <strong>Azure Storage</strong><br>
    You can create a blob container in Azure storage to store diagnostics.
  </li>
</ul>

	
