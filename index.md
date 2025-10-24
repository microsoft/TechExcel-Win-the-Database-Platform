---
title: Introduction
layout: home
nav_order: 1
---

# TechWorkshop L300: Win the database acceleration

This lab is designed to help you develop advanced skills in database management and AI integration. You'll work with several key products, including Microsoft Azure Cosmos DB, Azure Database for PostgreSQL, and AI integration tools. The exercises in this lab are independent of eachother and each of them is based on an individual case study.

In this lab, you'll first build a serverless, AI-powered application using data from Azure Cosmos DB. You'll learn how to set up and configure Cosmos DB, integrate AI models, and create a serverless application that leverages these technologies. Then you'll migrate an on-premises PostgreSQL server to Azure Database for PostgreSQL, with the exercise guiding you through setting up the Azure environment, configuring the PostgreSQL server, and performing the migration to ensure a smooth transition to the cloud. Additionally, you'll integrate AI functionality into PostgreSQL by implementing AI models, integrating them with PostgreSQL, and optimizing queries to enhance database performance and provide intelligent insights.

By the end of this lab, you'll have hands-on experience with cloud-based database management, AI integration, and the skills to build and optimize modern, intelligent applications.

## Architecture


### Build a serverless, AI RAG application using data from Azure Cosmos DB
![Diagram depicts the architecture of a Copilot with Azure OpenAI Service, Azure CosmosDB for NoSQL and Azure App Service with Semantic Kernel](media/AzureCosmosDB-architecture.png)

### Integrate AI functionality into PostgreSQL
![Diagram depicts the architecture for integrating GraphRag on Azure Database for PostgreSQL](media/PostgreSQL-AI-architecture.png)

### Implement generative AI with Azure SQL and REST endpoints
![Diagram depicts the architecture for creating and storing embeddings in the Azure SQL Database](../../media/session-recommender-architecture.png)

### Migrate an on-premises PostgreSQL server to Azure Database for PostgreSQL
![Diagram depicts the architecture for migrating an on-premises PostgreSQL server to Azure Database for PostgreSQL flexible server through a virtual gateway and Azure Virtual network (Vnet 1)](media/PostgreSQL-migration-architecture.png)


## Exercises

This lab has the following exercises:
 - Set up, configure, and manage an SQL Managed Instance in Azure
 - Build a serverless, AI RAG application using data from Azure Cosmos DB 
 - Migrate an on-premises PostgreSQL server to Azure Database for PostgreSQL
 - Integrate AI functionality into PostgreSQL
 - Set up generative AI by integrating AI capabilities with an Azure SQL Database

The lab is available as GitHub pages here: [TechExcel: Win the Database Platform](https://aka.ms/AIDF_SS9294783_TEWintheDatabasePlatform_Lab_IOPage).

## Prerequisites

For running this lab you'll need:

**General requirements**
- Azure Subscription with required roles & quotas
- Microsoft Entra ID (Azure AD) for authentication
- Internet access and network security setup
- Azure Resource Requirements


For **Exercise 01: Build a serverless, AI RAG application using data from Azure Cosmos DB**:
- Azure Cosmos DB (NoSQL) with vector search
- Azure OpenAI for GPT-based chat
- .NET Aspire and AI orchestration

For **Exercise 02: Integrate AI functionality into PostgreSQL**:
- Azure PostgreSQL Flexible Server
- pgvector, azure_ai, and pg_diskann extensions
- Azure OpenAI integration for AI queries

For **Exercise 03: Implement generative AI with Azure SQL and REST endpoints**:
- Azure Subscription (Owner or Contributor permissions)
- Azure SQL Database (Supports External REST Endpoint Invocation preview feature)
- Azure OpenAI Resource (GPT-4, text-embedding-ada-002, DALL-E 3 models)
- Azure AI Content Safety service
- Visual Studio Code (with SQL extension)


For **Exercise 04: Migrate an on-premises PostgreSQL server to Azure Database for PostgreSQL**:
- Azure PostgreSQL Flexible Server (v16)
- Azure Virtual Network and VPN Gateway
- Private DNS zone and SSL certificates for migration
- Visual Studio Code or Visual Studio 2022
- .NET SDK (8.0+), .NET Aspire
- Azure CLI and Azure Cosmos DB SDK
- pgAdmin 4 and PostgreSQL CLI
- Azure VPN Client and SSL certificates for migration