# ☁️ Azure Portfolio Website Deployment

![Azure](https://img.shields.io/badge/Microsoft-Azure-0078D4?logo=microsoftazure&logoColor=white)
![Windows Server](https://img.shields.io/badge/Windows-Server-blue)
![IIS](https://img.shields.io/badge/Web%20Server-IIS-success)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![HTTPS](https://img.shields.io/badge/HTTPS-SSL%2FTLS-green)

# Azure Portfolio Website Deployment

> Deploying a personal portfolio website on **Microsoft Azure** using a **Windows Server Virtual Machine**, **Internet Information Services (IIS)**, **Remote Desktop Protocol (RDP)**, **Azure Networking**, **Public IP**, **Azure DNS**, and **Network Security Groups (NSG)**.

---

# 📌 Overview

This project demonstrates the complete deployment of a personal portfolio website on **Microsoft Azure Cloud**.

Instead of hosting the website locally, the application is deployed on a **Windows Server Virtual Machine**, configured using **Internet Information Services (IIS)**, and made accessible over the internet through an **Azure Public IP** and **Azure DNS**.

The project also explores **HTTP & HTTPS communication**, **SSL certificate configuration**, and Azure networking concepts involved in deploying a real-world web application.

This project provided practical experience with cloud infrastructure, Windows Server administration, web server configuration, and website deployment.

---

# 🎯 Project Objective

The primary objective of this project is to understand how cloud infrastructure is used to deploy real-world applications.

Rather than simply creating Azure resources, the goal is to build an environment where users can securely access an application from anywhere over the internet.

---

# 🛠️ Technologies Used

- Microsoft Azure
- Windows Server 2025
- Internet Information Services (IIS)
- Remote Desktop Protocol (RDP)
- HTML5
- CSS3
- JavaScript
- HTTP
- HTTPS (SSL/TLS)

---

# ☁️ Azure Services Used

| Azure Service | Purpose |
|---------------|---------|
| Resource Group | Organizes all Azure resources |
| Windows Server Virtual Machine | Hosts the portfolio website |
| Public IP Address | Enables internet accessibility |
| Azure DNS | Provides a public hostname |
| Network Security Group (NSG) | Controls HTTP (80), HTTPS (443), and RDP (3389) traffic |
| Virtual Network (VNet) | Enables communication between Azure resources |

---

# 🏗️ Project Architecture

```text
                     Internet
                          │
                          ▼
              Azure DNS / Public IP
                          │
                          ▼
      Azure Network Security Group (NSG)
             HTTP (80) | HTTPS (443)
                          │
                          ▼
      Windows Server 2025 Virtual Machine
                          │
                          ▼
      Internet Information Services (IIS)
                          │
                          ▼
       Portfolio Website (HTML/CSS/JavaScript)
```

---

# ⚙️ Deployment Steps

- Created an Azure Resource Group
- Provisioned a Windows Server 2025 Virtual Machine
- Connected to the VM using Remote Desktop Protocol (RDP)
- Installed and configured Internet Information Services (IIS)
- Uploaded website files to the IIS web root directory
- Configured Azure Public IP and Azure DNS
- Configured Azure Network Security Group (NSG) rules
- Enabled HTTP (Port 80)
- Enabled HTTPS (Port 443)
- Created and configured an SSL certificate in IIS
- Configured HTTPS bindings
- Tested website accessibility from desktop and mobile devices
- Explored Let's Encrypt integration for trusted SSL certificates

---

# 🌐 Live Website

### HTTP (Working)

👉 **http://104.214.169.160**

### HTTPS (Under SSL Configuration)

👉 **https://lakshana-portfolio.eastasia.cloudapp.azure.com**

> **Note:** HTTPS has been configured using an SSL certificate. A trusted Certificate Authority (CA) certificate is currently being configured, so some browsers may display a security warning.

---

# 🚧 Challenges Faced

During deployment, several real-world challenges were encountered and explored, including:

- Configuring IIS on Windows Server
- Understanding Azure networking components
- Configuring Network Security Group (NSG) rules
- Understanding the difference between HTTP and HTTPS
- Creating and binding SSL certificates in IIS
- Troubleshooting browser security warnings
- Exploring Let's Encrypt certificate generation
- Testing website accessibility across desktop and mobile devices

These challenges provided valuable hands-on experience in cloud deployment and web server administration.

---

# 📚 Key Learnings

Through this project, I gained practical experience with:

- Microsoft Azure Fundamentals
- Azure Resource Management
- Windows Server Administration
- Azure Virtual Machine Deployment
- IIS Web Server Configuration
- Remote Desktop Protocol (RDP)
- Azure Networking
- Public IP Configuration
- Azure DNS
- Network Security Groups (NSG)
- HTTP & HTTPS Communication
- SSL/TLS Certificates
- Website Deployment
- Cloud Infrastructure Fundamentals

---

# 🚀 Future Improvements

- Configure a trusted SSL certificate using Let's Encrypt
- Connect a custom domain
- Enable automatic HTTP to HTTPS redirection
- Deploy backend services
- Integrate Azure SQL Database
- Implement CI/CD using GitHub Actions
- Monitor application availability using Azure Monitor

---

---

# 👩‍💻 Author

**Lakshana R**

Electronics and Communication Engineering (ECE)

Interested in:

- Cloud Computing
- Embedded Systems
- Internet of Things (IoT)
- Artificial Intelligence

---

⭐ **If you found this project interesting, feel free to star this repository!**
