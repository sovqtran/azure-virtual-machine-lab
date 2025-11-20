<p align="center">
  <img src="https://learn.microsoft.com/en-us/azure/architecture/icons/media/services/Virtual-Machines.svg" width="160" alt="Azure Virtual Machine Icon">
</p>

<h1 align="center">Step-by-Step Guide: Creating Virtual Machines (VM) with Microsoft Azure</h1>

<p align="center">
  Hands-on lab for deploying, configuring, and connecting to a Windows 11 Azure Virtual Machine.
</p>


# Azure Virtual Machine Lab

This repository documents my process of creating and accessing a Virtual Machine in Microsoft Azure.

More updates coming soon.

## Prerequisites

Before starting this lab, make sure you have the following:

- A Microsoft Azure account  
- Internet connection  
- A computer running Windows 10/11  
- Remote Desktop Connection (RDP) installed — included by default on Windows  


## Technologies Used

This lab makes use of the following technologies and tools:

- Microsoft Azure Portal  
- Azure Virtual Machines (Compute)  
- Windows 11 (for the VM)  
- Remote Desktop Protocol (RDP)  
- Web browser (Microsoft Edge, Chrome, or similar)
  
## Creating the Virtual Machine

The following section outlines the process for creating a Windows Virtual Machine in Microsoft Azure.  
This includes selecting a resource group, choosing an operating system, configuring the VM size,  
and preparing login credentials that will later be used to access the machine via Remote Desktop.

### Step 1: Log Into the Azure Portal

Start by signing into the Microsoft Azure Portal.  
If you do not have an account yet, you can create one using Microsoft's free trial, which includes $200 in credits for the first 30 days.

<p align="center">
  <img src="images/azure-portal-login.png" width="80%" alt="Azure Portal Login"/>
</p>

## Accessing the Virtual Machine (Windows 11)

To connect to your Azure Virtual Machine from a Windows 11 computer:

1. Open the **Start Menu**  
2. Type **Remote Desktop Connection**  
3. Select the RDP app (preinstalled on Windows 11)  
4. Enter the Public IP address of your Azure VM  
5. Authenticate using the username and password you created during VM setup
