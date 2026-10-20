Azure Hub and Spoke Landing Zone
Overview

This project demonstrates the design and implementation of a secure Microsoft Azure Landing Zone using a Hub-and-Spoke network architecture.

Key Features:

    Microsoft Entra ID
    Azure RBAC
    Azure Policy
    Hub and Spoke Networking
    Azure Bastion
    Azure Key Vault
    Managed Identities
    Private Endpoints
    Private DNS
    Azure Monitor
    Log Analytics Workspace
    Recovery Services Vault
    Azure Backup

Architecture
The environment follows a Hub-and-Spoke architecture consisting of a central Hub VNet and dedicated Application and Management spoke networks.

Architecture Diagram
<img width="1522" height="794" alt="HubAndSpokeArchitecture" src="https://github.com/user-attachments/assets/d90c1e07-bf92-4051-ba1d-19b2e69f26d9" />

Business Requirements

    Secure administration of workloads
    Centralised identity management
    Governance through Azure Policy
    Monitoring and alerting
    Backup and recovery
    Private access to Azure Storage

Documentation

    Business Scenario
    Technical Design Document
    Architecture Diagram

Future Enhancements

    Full Terraform deployment
    Remote Terraform State
    CI/CD Implementation
