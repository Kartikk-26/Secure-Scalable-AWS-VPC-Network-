# 🚀 Successfully Built a Secure & Scalable AWS VPC Network! 🔥🌐

## 📌 Project Overview
This project focuses on designing and deploying a fully functional **AWS Virtual Private Cloud (VPC)** to ensure **secure, scalable, and efficient cloud networking**. 

Through hands-on implementation, I gained expertise in AWS networking, subnet segmentation, security configurations, private cloud infrastructure, database isolation, and inter-region connectivity.

## 🔍 Key Features & Implementation

### ✅ **Understanding VPC & Its Usage**
- Explored how **VPCs provide network isolation, security, and controlled access** in AWS.

### ✅ **Created a Custom VPC**
- Defined my own VPC named **`my-vpc-1`** with a **custom IPv4 CIDR block**.

### ✅ **Configured Subnets for Efficient Networking**
- **Public subnet** for internet-facing resources.
- **Private subnet** for internal workloads.

### ✅ **Set Up an Internet Gateway**
- Attached an **Internet Gateway** to allow instances in the **public subnet** to securely access the internet.

### ✅ **Created Route Tables & Associations**
- Configured a **custom route table** for the VPC.
- Added a route to **connect the Internet Gateway** for external access.

### ✅ **Launched an EC2 Instance in Public Subnet**
- Instance **`test1`**, assigned a **public IP**, and verified **internet connectivity**.

### ✅ **Built a Secure Private Subnet for Database**
- Created **Subnet 2** to **restrict database access** to private IPs only.

### ✅ **Deployed a NAT Gateway for Private Subnet**
- Placed a **NAT Gateway** in Subnet 1, enabling **outbound internet access** for private instances while maintaining security.

### ✅ **Launched a Private Instance in Subnet 2**
- Created an **EC2 instance without a public IP**, making it accessible only within the **private network**.

### ✅ **Installed a Database in the Private Subnet**
- Set up a **database server** that is only reachable via the private IP of **Subnet 2**, ensuring **strong security practices**.

### ✅ **Established SSH Connection via Bastion Host**
- Logged into **Instance 1 (Public Subnet)**.
- Generated a **key pair (`Key.pem`)**.
- Set permissions and **used SSH to access the private instance** securely.

### ✅ **Implemented VPC Peering for Cross-Region Connectivity**
- Set up a **VPC Peering Connection** to enable **secure communication between two VPCs** in different AWS regions.
- Configured **Requester and Accepter VPCs** and verified the **peering connection**.

## 🚀 Why This Project Matters?
- **Essential skill for Cloud Engineers & DevOps Professionals**.
- Strengthens expertise in **AWS networking, infrastructure security, and cloud scalability**.
- Demonstrates best practices for **secure VPC design & inter-region connectivity**.

## 🛠️ Tech Stack
- **AWS VPC**
- **AWS EC2**
- **AWS Subnets (Public & Private)**
- **Internet & NAT Gateways**
- **Route Tables & Peering**
- **Bastion Host for Secure SSH Access**
- **Private Database Hosting**

## 📂 Folder Structure
```
├── aws-vpc-project/             # Main project folder
│   ├── vpc/                     # Contains VPC setup-related images
│   │   ├── Setting Up VPC Images
│   ├── vpc-peering/             # Contains VPC Peering setup images
│   │   ├── Setting Up VPC Peering Images
│
├── README.md                    # Project documentation
├── assets/                      # Additional resources or shared file

```

## 📌 How to Use This Project?
1. Clone the repository:
   ```sh
   git clone https://github.com/Kartikk-26/Secure-Scalable-AWS-VPC-Network-.git
   ```
2. Navigate to the project directory:
   ```sh
   cd aws-vpc-project
   ```
3. Follow the **AWS setup guide** in the repository to deploy your own **secure & scalable VPC**.

## 🎯 Expected Outcomes

- ✅ Seamless cross-VPC communication via VPC Peering.
- ✅ Well-structured AWS VPC architecture with public and private subnets.
- ✅ Enhanced security with properly configured Security Groups and NACLs.
- ✅ Hands-on experience in AWS networking and infrastructure management. 
- ✅ Successful Connection to Private DB![Image1](./Assests/Successful%20Connection%20to%20Private%20DB.png)
- ✅ Internet Connectivity of Private Database![Image2](./Assests/Internet%20Connectivity%20of%20Private%20Database.png)

## 📢 Let's Connect!
- Stay updated on [LinkedIn](https://www.linkedin.com/in/-kartikjain/) for more DevOps projects and insights.
- Follow along as I explore **Cloud Infrastructure, Ansible Automation, and DevOps practices**.
- Let's collaborate and build scalable solutions together!

---
### 🌟 If you found this project helpful, don’t forget to **star⭐** this repo!
---
