# AWS VPC Network Setup Project

## 📌 Project Overview
This project demonstrates the creation of an Amazon Virtual Private Cloud (VPC) using AWS. The VPC provides a logically isolated network environment in the cloud.

## ❓ What is a VPC?
A Virtual Private Cloud (VPC) is a private network in AWS where you can launch and manage resources securely.

## 🎯 Objective
- Create a VPC in AWS
- Configure a CIDR block (10.0.0.0/16)
- Understand basic AWS networking components

## 🧱 Steps Performed
1. Logged into AWS Management Console  
2. Navigated to VPC service  
3. Clicked "Create VPC"  
4. Selected "VPC only"  
5. Set CIDR block to 10.0.0.0/16  
6. Created the VPC successfully  

## 🧠 Key Concepts Learned
- VPC (Virtual Private Cloud)
- CIDR block
- AWS networking fundamentals

## ⚙️ Automatically Created Components
When the VPC was created, AWS also automatically generated the following default networking components:

- **Main Route Table** – Controls traffic routing within the VPC  
- **Network Access Control List (NACL)** – Acts as a firewall at the subnet level  
- **Security Group Framework** – Virtual firewall for controlling inbound and outbound traffic to resources  
- **DHCP Option Set** – Provides network configuration such as DNS settings and domain names for instances  

## 📸 Screenshots
![VPC Setup](Screenshot%202026-06-07%20191203.png)

## 🚀 Conclusion
This project helped me understand the basics of AWS networking and how cloud infrastructure is structured using VPCs.
