# azure-cloud-file-upload-system
Cloud-based file upload system using Azure VM and Blob Storage

Azure Blob Storage File Upload Web Application

This project is a cloud-based file upload web application hosted on a Linux virtual machine in Microsoft Azure. The system allows users to upload files through a simple and professional web interface, and the uploaded files are securely stored in Azure Blob Storage. The application also displays a dynamic list of uploaded files, similar to a lightweight cloud storage platform.

The project demonstrates the integration of multiple Azure cloud services, including Azure Virtual Machines, Azure Blob Storage, Shared Access Signatures (SAS), and web hosting using Apache on Ubuntu Linux.

Project Objectives
- Host a website on an Azure Linux Virtual Machine
- Create and configure Azure Blob Storage
- Upload files directly from the website to Azure Blob Storage
- Secure storage access using SAS tokens
- Display uploaded files dynamically on the webpage
- Understand cloud storage integration using JavaScript

Technologies Used

| Technology             | Purpose                                            |
| ---------------------- | -------------------------------------------------- |
| Microsoft Azure Portal | Cloud platform used to create and manage resources |
| Ubuntu Server          | Linux server hosting the website                   |
| Apache HTTP Server     | Web server used to host the application            |
| JavaScript             | Handles file upload and storage communication      |
| HTML & CSS             | Frontend structure and design                      |
| Azure Blob Storage     | Stores uploaded files securely                     |
| SAS Token              | Provides secure temporary access to Blob Storage   |
| PuTTY                  | SSH connection to Linux VM                         |


System Workflow
1. The user accesses the hosted website through the Azure VM public IP address.
2. The user selects a file using the upload interface.
3. JavaScript creates an authenticated request using the SAS token.
4. The file is uploaded directly to Azure Blob Storage using HTTP PUT requests.
5. After upload, the application retrieves and displays all uploaded files from the Blob container.

Key Features
- Secure cloud file uploads
- Responsive and clean user interface
- Dynamic file listing
- Linux-based web hosting
- Direct browser-to-cloud storage communication
- SAS-based authentication for improved security

Security Implementation
Instead of exposing Azure Storage Account keys, the project uses Shared Access Signature (SAS) tokens. SAS tokens provide temporary and limited access permissions such as:
  Read
  Write
  Add
  List
This approach improves security by allowing controlled access to Azure Blob Storage without revealing sensitive account credentials.

Learning Outcomes
Through this project, the following cloud computing concepts were learned:
- Creating and configuring Azure Virtual Machines
- Hosting websites on Linux servers
- Using Apache web server
- Managing Azure Blob Storage containers
- Generating and configuring SAS tokens
- Implementing CORS settings
- Integrating frontend applications with cloud storage using JavaScript

Conclusion
This project successfully demonstrates how cloud infrastructure and storage services can be integrated to build a functional file upload platform. By combining Azure Virtual Machines, Blob Storage, and JavaScript-based frontend development, the application provides a practical example of modern cloud-based web hosting and storage integration. The project also highlights secure cloud communication techniques using SAS authentication.

Medium Documentation
Read the complete article here:
https://medium.com/@lasandimihara2/hosting-a-file-upload-website-on-azure-linux-vm-with-blob-storage-56a09c91263d
