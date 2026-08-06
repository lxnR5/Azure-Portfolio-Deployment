# ☁️ Azure Portfolio Website Deployment

![Azure](https://img.shields.io/badge/Microsoft-Azure-0078D4?logo=microsoftazure&logoColor=white)
![Windows Server](https://img.shields.io/badge/Windows-Server-blue)
![IIS](https://img.shields.io/badge/Web%20Server-IIS-success)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

# Azure Portfolio Website Deployment

> Deploying a personal portfolio website on **Microsoft Azure** using a **Windows Server Virtual Machine**, **Internet Information Services (IIS)**, **Remote Desktop Protocol (RDP)**, **Public IP**, and **Network Security Group (NSG)**.

---

## 📌 Overview

This project demonstrates the complete deployment of a personal portfolio website on **Microsoft Azure Cloud**.

Instead of hosting the website locally, the application is deployed on an **Azure Windows Server Virtual Machine**, configured using **Internet Information Services (IIS)**, and made accessible over the internet through an **Azure Public IP** and **Azure DNS**.

This project helped me gain practical experience with cloud infrastructure, virtual machine provisioning, web server configuration, and website deployment.

---

## 🎯 Project Objective

The primary objective of this project is to understand how cloud infrastructure is used to deploy real-world applications.

Rather than simply creating Azure resources, the goal is to build an environment where users can access an application from anywhere over the internet.

---

## 🛠️ Technologies Used

- Microsoft Azure
- Windows Server 2025
- Internet Information Services (IIS)
- Remote Desktop Protocol (RDP)
- HTML5
- CSS3
- JavaScript

---

## ☁️ Azure Services Used

| Azure Service | Purpose |
|---------------|---------|
| Resource Group | Organizes all project resources |
| Virtual Machine | Hosts the website |
| Public IP | Enables internet access |
| Azure DNS | Provides a public domain name |
| Network Security Group (NSG) | Controls inbound and outbound traffic |
| Virtual Network (VNet) | Enables secure communication between Azure resources |

---

## 🏗️ Project Architecture

```text
                Internet
                    │
                    ▼
        Azure Public DNS / Public IP
                    │
                    ▼
      Network Security Group (NSG)
                    │
                    ▼
      Windows Server Virtual Machine
                    │
                    ▼
          IIS Web Server
                    │
                    ▼
      Portfolio Website (HTML/CSS/JS)
```

---

## ⚙️ Deployment Steps

- Created an Azure Account
- Created a Resource Group
- Provisioned a Windows Server Virtual Machine
- Connected to the VM using Remote Desktop (RDP)
- Installed and configured Internet Information Services (IIS)
- Uploaded website files to the IIS web directory
- Configured networking using Public IP and NSG
- Verified successful deployment through the Azure public URL

---

## 📸 Project Screenshots

### Azure Fundamentals Learning

> *(Add Screenshot)*

---

### Creating Virtual Machine

> *(Add Screenshot)*

---

### Connecting through Remote Desktop

> *(Add Screenshot)*

---

### Windows Server

> *(Add Screenshot)*

---

### Portfolio Website Running on Azure

> *(Add Screenshot)*

---

## 🌐 Live Website

**Portfolio Website**

👉 **http://lakshana-portfolio.eastasia.cloudapp.azure.com/**

---

---

## 📚 Key Learnings

Through this project, I gained hands-on experience with:

- Microsoft Azure Fundamentals
- Azure Virtual Machine Deployment
- Windows Server Administration
- IIS Configuration
- Remote Desktop (RDP)
- Azure Networking
- Public IP Configuration
- Network Security Groups
- Website Deployment
- Cloud Infrastructure

---

## 👨‍💻 Author

**Lakshana R**

Electronics and Communication Engineering (ECE)

Passionate about Cloud Computing, Embedded Systems, IoT, and AI.

---

⭐ If you found this project interesting, feel free to star this repository!
