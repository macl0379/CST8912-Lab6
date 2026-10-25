# CST8912 Lab 6

**Student Name**: Collin MacLeod
**Student ID**: macl0379
**Course**: CST8912 Cloud Solutions Architecture
**Semester**: Fall 2026

## Introduction

Azure Private Link provides private connectivity from a virtual network to Azure platform as a service (PaaS), customer-owned, or Microsoft partner services. It simplifies the network architecture and secures the connection between endpoints in Azure by eliminating data exposure to the public internet.

Private Endpoint is the key technology behind Private Link. Private Endpoint is a network interface that enables a private and secure connection between your virtual network and an Azure service. In other words, Private Endpoint is the network interface that replaces the resource's public endpoint.

## Screenshots

![Review Screen for Virtual Network creation show a Bastion and adding it as it the public IP](/Screenshots/Creating%20Virtual%20Network%20with%20Bastion.png  "Review Screen for Virtual Network creation show a Bastion and adding it as it the public IP")
*Review Screen for Virtual Network creation show a Bastion and adding it as it the public IP*

![Settings for Subnet, using default starting addrress of 10.0.2.0, with private subnet enabled](/Screenshots/Setting%20for%20Subnet.png "Settings for Subnet, using default starting addrress of 10.0.2.0, with private subnet enabled")
*Settings for Subnet, using default starting addrress of 10.0.2.0, with private subnet enabled*

![Review screen for creating storage account with locally redundant storage](/Screenshots/Create%20Storage%20Account.png "Review screen for creating storage account with locally redundant storage")
*Review screen for creating storage account with locally redundant storage*

![Dialog for disabling public access to storage container](/Screenshots/Disabling%20Public%20Access.png "Dialog for disabling public access to storage container")
*Dialog for disabling public access to storage container*

![Review Screen for creating private endpoint with resource connection to cst8912storage, virtual network of 8912-vnet1 and Subnet of Subnet-1-8912](/Screenshots/Private%20Endpoint%20Creation.png "Review Screen for creating private endpoint with resource connection to cst8912storage, virtual network of 8912-vnet1 and Subnet of Subnet-1-8912")
*Review Screen for creating private endpoint with resource connection to cst8912storage, virtual network of 8912-vnet1 and Subnet of Subnet-1-8912*

![Subnet network policy settings screen showing network policies setting for all private endpoints in this ubnet enabled](/Screenshots/Subnet%20Network%20Policy.png "Subnet network policy settings screen showing network policies setting for all private endpoints in this ubnet enabled")
*Subnet network policy settings screen showing network policies setting for all private endpoints in this subnet enabled*

![Review screen for creating virtual machine with Windows Server 2022 Datacenter and smallest available size and no public inbound ports](/Screenshots/Creating%20VM.png "Settings for Subnet, using default starting addrress of 10.0.2.0, with private subnet enabled and no public inbound ports")
*Settings for Virtual Machine, using default starting addrress of 10.0.2.0, with private subnet enabled and no public inbounds ports*

![Storage Account storage access keys with details hidden](/Screenshots/Storage%20Account%20Access%20Keys.png "Storage Account storage access keys with details hidden")
*Storage Account storage access keys with details hidden*

![Overview of containers including con-cst8911 (mistakenly labelled) that sit in storage account cst8912storage](/Screenshots/Container%20Overview.png "Overview of containers including con-cst8911 (mistakenly labelled) that sit in storage account cst8912storage")
*Overview of containers including con-cst8911 (mistakenly labelled) that sit in storage account cst8912storage*

![Output of NSlookup call on cst8912storage](/Screenshots/NS%20Lookup%20Results.png "Output of NSlookup call on cst8912storage")
*Output of NSlookup call on cst8912storage*

![Storage account access through Microsoft Azure Storage Explorer showing container and blob](/Screenshots/Storage%20container%20through%20Azure%20Storage%20Access.png "Storage account access through Microsoft Azure Storage Explorer showing container and blob")
*Storage account access through Microsoft Azure Storage Explorer showing container and blob*

![Overview of resources created during lab in resource group CST8912demo](/Screenshots/Resource%20Group%20Overview.png "Overview of resources created during lab in resource group CST8912demo")
*Overview of resources created during lab in resource group CST8912demo*

![Resource group empty after cleanup](/Screenshots/Resource%20Cleanup.png "Resource group empty after cleanup")
*Resource group empty after cleanup*

