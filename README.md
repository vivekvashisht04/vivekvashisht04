## Welcome to My GitHub Profile!

<div align="center">
  <img src="https://github.com/user-attachments/assets/bad76ba9-2457-4199-b7f6-13f64df13154" alt="Profile Animation">
</div>

## About Me:

I am currently pursuing a diploma in ITS (Information Technology Services) with a keen interest in cloud computing. I hold multiple cloud certifications:

- **Microsoft Certified: Azure Administrator Associate (AZ-104)**
- **Microsoft Certified: Azure Fundamentals (AZ-900)**
- **AWS Certified Cloud Practitioner (CLF-CO2)**
- **HashiCorp Certified: Terraform Associate (HCTA0-003)** ☁️

My goal is to continually upgrade my skills and knowledge in cloud technologies. I plan to attain further certifications and develop projects to showcase my hands-on cloud skills 🚀. As an aspiring Cloud Engineer and Administrator, I view cloud technology as pivotal to today's digital era. I am actively seeking hands-on experiences and opportunities in cloud solutions. With a solid history of academic dedication, I am committed to excellence in the IT field. I am eager to connect with professionals and peers for collaboration and insights in the cloud domain 🌐.

## Real-World Experience:

I have completed the following 11 labs as part of my coursework:

- **Azure Cost Management Tools:** Managing and organizing Azure resources efficiently.
- **Azure Identities:** Managing Azure Active Directory and role-based access controls.
- **Azure Virtual Machines:** Setting up and managing virtual machines within the Azure ecosystem.
- **Azure Containers:** Container deployment and management using Azure Kubernetes Service and Azure Container Instances.
- **Azure App Service:** Creating and managing web apps and integrating with Azure services.
- **JSON and Bicep:** Infrastructure as Code (IaC) using JSON and Bicep for resource deployment.
- **Azure Storage Services:** Managing Azure storage solutions, including blobs, files, and static websites.
- **Azure File Services:** Setting up and managing Azure File Shares, including connection, synchronization, and creating snapshots for data recovery.
- **Azure Network Services:** Configuring Azure's networking components, including virtual networks, subnets, and DNS, with practical exercises on network security.
- **Azure Security Tools:** Exploring Azure's security features by setting up Bastion for secure access, configuring the Azure Firewall, and managing DDoS protection.
- **Azure Performance Tools:** Monitoring and optimizing Azure services using Azure Monitor, setting up alerts, and implementing disaster recovery strategies with Azure Site Recovery and Load Balancers.

## Projects:

I have started working on projects based on the scope of AZ-104 to demonstrate my hands-on capabilities and skills. Here is a highlight of a recently completed project:

### 🌟 Project: Onboard Automator

**Objective:** Automate employee onboarding to Microsoft Entra ID (Azure AD) and assign Azure resources.

**Azure Services Used:** Azure AD, Azure Logic Apps, Azure Resource Manager, Azure Email Service.

**🔧 Key Features:**

1. **Microsoft Entra ID (Azure AD) Setup:** Configured Azure AD for managing identities.
2. **Logic App Workflow:** Designed a workflow triggered by new email notifications indicating a new hire.
3. **Variable Initialization:** Extracted and cleaned user data from emails.
4. **User Creation:** Automated the creation of users in Azure AD.
5. **Group Assignment:** Assigned new users to appropriate groups based on their department.
6. **Resource Provisioning:** Provisioned personalized Ubuntu VMs for new employees using ARM templates.
7. **Welcome Email:** Sent automated welcome emails with access details to new hires.
8. **Monitoring and Review:** Ensured smooth operations through monitoring and reviewing the onboarding process.




### 🌟 Project: ShareSafely

**Objective:** Provide a secure platform for file sharing with time-limited access control.

**Azure Services Used:** Azure Blob Storage, Azure Web Apps, Azure Key Vault, Azure Monitor, Azure Functions.

🔧 **Key Features:**

- **Azure Blob Storage Setup:** Configured secure file storage with encryption and access controls.
- **Web Application Development:** Developed using Python and Flask, creating a user-friendly interface for uploading and sharing files.
- **Secure Credentials:** Utilized Azure Key Vault to securely manage sensitive credentials.
- **Automated Cleanup:** Implemented Azure Functions to automatically clean up expired files, ensuring efficient storage management.
- **Monitoring and Alerts:** Set up Azure Monitor to track performance metrics and configure alerts for critical issues.




### 🌟 Project: VM Fleet Commander

**Objective:** Implement an infrastructure-as-code approach to provision and manage virtual machines in Azure, using ARM templates and Bicep.

**Azure Services Used:** Azure Virtual Machines, Azure Resource Manager (ARM), Bicep.

🔧 **Key Features:**

- **Initial Setup:** Configured Azure CLI with Bicep support and set up Git for version control to track changes in Bicep and ARM templates.
- **Bicep Basics:** Practiced converting ARM templates to Bicep using az bicep decompile, enhancing understanding and efficiency.
- **Resource Group Creation:** Defined a Bicep file (resource-group.bicep) to create an Azure Resource Group for VMs, facilitating organized resource management.
- **Virtual Machine Provisioning:** Created a Bicep module (vm.bicep) for deploying Azure VMs with parameterized inputs, including VM size, name, and region. Implemented loops for multiple VM instances.
- **Network Resources:** Designed a Bicep module (network.bicep) for networking resources like Virtual Network, Subnet, NIC, Public IP, and NSG, ensuring secure and efficient networking.
- **Deployment:** Validated and deployed Bicep templates across development, testing, and production environments, ensuring reproducibility and consistency.
- **Maintenance & Updates:** Updated parameters, redeployed resources, and ensured regular updates to Bicep and Azure CLI, maintaining infrastructure health.
- **Cleanup:** Deleted resource groups after testing to avoid unnecessary costs using az group delete.




### 🌟 Project: NetMaze Explorer

**Objective:** Design and implement a hybrid networking environment where on-premises networks connect securely to Azure resources, showcasing expertise in Azure networking services.

**Azure Services Used:** Azure Virtual Networks, Azure VPN Gateway, Network Security Groups (NSGs), Azure Bastion, Azure Private Link, Azure DNS, Azure Load Balancer.

🔧 **Key Features:**

- **Initial Setup:** Configured resource groups and virtual networks in Azure regions to simulate both on-premises and cloud environments, establishing a foundational network structure.
- **Site-to-Site VPN:** Established a secure VPN connection between on-premises networks and Azure using Azure VPN Gateway and Local Network Gateway, ensuring encrypted data transmission.
- **Resource Deployment:** Deployed multiple virtual machines across different subnets, simulating a full-stack environment with Web, Database, and Admin VMs to mimic real-world scenarios.
- **Network Access Control:** Enforced Network Security Groups (NSGs) to control inbound and outbound traffic, ensuring secure access to resources and minimizing exposure to potential threats.
- **Secure Connectivity:** Implemented Azure Bastion for secure RDP and SSH access to VMs without exposing them to the public internet, enhancing security and administrative access.
- **Private Access:** Utilized Azure Private Link for secure, private access to Azure PaaS services like Azure SQL Database, ensuring sensitive data remains within a protected network.
- **Load Balancing:** Configured Azure Load Balancer to distribute traffic across VMs in the WebApp subnet, improving reliability, availability, and overall performance.
- **Monitoring & Alerts:** Enabled diagnostics and monitoring on VPN Gateways, NSGs, and other critical resources, and set up alerts for suspicious activities, ensuring proactive management and security.




### 🌟 Project: InsightScape

**Objective:** Design and deploy an integrated monitoring and maintenance framework using Azure services to ensure comprehensive visibility, security, and performance optimization across cloud environments.

**Azure Services Used:** Azure Monitor, Azure Log Analytics, Kusto Query Language (KQL), Azure Application Insights, Azure Network Watcher, Azure Security Center, Azure Backup, Azure Alerts.

🔧 **Key Features:**

- **Initial Setup:** Configured core Azure resources, including Virtual Machines, Web App, Blob Storage, Logic App, and Networking Resources, to create a foundation for monitoring and maintenance.
- **Resource Monitoring Integration:** Deployed Azure Monitor with VM Insights, integrating monitoring for VMs, Web App, and Logic App to provide health, performance, and usage insights.
- **Log Analytics & KQL Queries:** Utilized Azure Log Analytics with Kusto Query Language (KQL) to craft queries for real-time insights across infrastructure—monitoring metrics such as CPU utilization, memory availability, disk space, and workflow actions.
- **Application Insights:** Integrated Application Insights with the Web App for in-depth analysis, including performance, response times, user interactions, failures, and live metrics.
- **Network Monitoring:** Leveraged Azure Network Watcher tools like Packet Capture, NSG Diagnostics, and Topology View to monitor and visualize network connectivity, ensuring optimal performance and identifying bottlenecks.
- **Security & Compliance:** Strengthened resource security using Azure Security Center and Microsoft Defender for Cloud, addressing vulnerabilities, securing VMs, encrypting disks, and implementing secure networking rules.
- **Custom Alerts:** Configured alerts for anomalies, including failed RDP login attempts, Logic App execution failures, and HTTP 5xx errors, ensuring proactive incident response and reduced downtime.
- **Backup & Disaster Recovery:** Implemented Azure Backup for VM recovery, including a successful disaster recovery test by restoring a deleted VM using Azure Recovery Services.




## Contact:
Thank you for visiting my profile! 
Let's connect and explore the world of cloud computing together.
LinkedIn: https://www.linkedin.com/in/vivek-vashisht04/

<div align="center">
  <img src="https://media3.giphy.com/media/v1.Y2lkPTc5MGI3NjExOXhxcXM2cTczazFvdXhrY2hoZTE5czRlenRsaWFkcW1paW93aDdhdyZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/KktZLPCI8d8j5TF2M0/giphy.webp" alt="Cloud Computing">
</div>
