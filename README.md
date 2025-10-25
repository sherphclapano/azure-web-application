# Project Overview
## Cybersecurity – Web Application Deployment and Security Configuration
**Platform:** Microsoft Azure <br>
**Project URL:** https://sclapano-securityresume.azurewebsites.net/

This project demonstrates the deployment, configuration, and security management of a web application hosted on Microsoft Azure. It was developed as part of a cybersecurity unit project to explore practical applications of cloud computing, web hosting, and cryptogrphic security within an enterprise environemnt.

### Project Description
The project involved creating and managing a PHP-based web application hosted on Azure using a free domain. The web app integrates front-end and back-end components and showcases the student's technical proficiency in cloud infrastructure, DNS management, and secure communications.

#### Key Components:
* Deployed via Azure App Service using a free domain.
* PHP 8.0 (Back-end)
* HTML structure with CSS styling and image directories for visual content.
* Configured with an IP address (20.211.64.11) hosted in the *Australia East* region.
* Verified through `nslookup`, resolving Azure's canonical names and authoritative records.

### Cloud & Security Configuration
#### Azure Services Used
* Implemented for secure management of keys, secrets, and certificates.
* Configured to enhance web application performance, enable global content delivery, and provide **Web Application Firewall (WAF)** integration.
* Includes geolocation-based filtering (e.g., blocking traffic from specific regions such as Canada).
* SSL offloading implemented to enhance performance and security. Azure-issued TLS certificates ensure data encryption for secure HTTPS connections.

### Cryptography & Certificates
* Self-signed and Azure-managed TLS certificate.
* DigiCert Global Root G2 (valid 01/08/2013 - 15/01/2038).
* To explore practical encryption, SSL offloading, and the implications of using self-signed vs CA-issued certificates.

### Learning Outcomes
Through this project, I gained hands-on experience in:
* Configuring cloud-hosted web applications using Azure.
* Managing domain settings, DNS records, and IP allocations.
* Understanding the role of Key Vaults, WAF, and Front Door in web security.
* Applying cryptographic principles and SSL/TLS security configurations.
* Recognising vulnerabilities such as HTTP host header injection and mitigating them using managed firewall rules.

### Repository Structure
```
project-root/
│
├── assets/
│   ├── css/          # Contains website styling
│   └── images/       # Contains visual assets
│
├── index.html        # Main website page
├── blog/             # Blog posts and sample content
└── README.md         # Project overview and documentation
```

## Disclaimer
This project was completed as part of a university cybersecurity module and is hosted temporarily for academic purposes. <br>

All resources deployed on Azure were created using a free-tier subscription, and any future costs will be managed or resources will be deleted upon project completion.
<br><br>

© 2025 Sherphylle Clapano. All Rights Reserved.



