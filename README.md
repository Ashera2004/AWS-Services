# EX NO: 2 : Cloud Storage Creation (S3), Launching EC2 Instance, and VPC in AWS  

**NAME:** A S Siddarth  
**REG NO:** 212224040316  

---

## Aim  
To create cloud storage using **Amazon S3**, launch an **EC2 instance**, and set up a **VPC (Virtual Private Cloud)** in AWS.  

---

## Procedure  

### Step 1: Create an S3 Bucket (Cloud Storage)  
1. Log in to the **AWS Management Console**.  
2. Open the **S3 Service**.  
3. Click **Create bucket**.  
4. Enter a **unique bucket name** and select a region.  
5. Configure options like versioning, encryption (optional).  
6. Set permissions (Public or Private access).  
7. Click **Create bucket**.  
8. Upload files to the bucket to verify storage.  

---

### Step 2: Launch an EC2 Instance (Virtual Server)  
1. Navigate to **EC2 Service** in the AWS Console.  
2. Click **Launch Instance**.  
3. Enter the **instance name**.  
4. Choose an **Amazon Machine Image (AMI)** (e.g., Amazon Linux 2, Ubuntu).  
5. Select an **instance type** (e.g., `t2.micro` under Free Tier).  
6. Configure instance details such as **VPC, subnet, and storage**.  
7. Add storage if needed.  
8. Configure **security group** (allow SSH, HTTP, HTTPS as required).  
9. Create or use an existing **key pair** for SSH access.  
10. Click **Launch Instance**.  
11. Connect to the instance using **SSH or AWS Console**.  

---

### Step 3: Create a VPC (Virtual Private Cloud)  
1. Go to the **VPC Service** in AWS Console.  
2. Click **Create VPC**.  
3. Enter a **VPC name** and choose an **IPv4 CIDR block** (e.g., `10.0.0.0/16`).  
4. Create **subnets** (Public and Private).  
5. Attach an **Internet Gateway** to the VPC.  
6. Update **Route Tables** to allow traffic from/to the internet.  
7. Associate the **EC2 instance** with the newly created VPC and subnet.  
8. Verify connectivity (e.g., ping or SSH).  

---

## Services Overview  

### 1. Amazon EC2 (Elastic Compute Cloud)  
**Features**  
- Scalable virtual servers in the cloud.  
- Supports multiple operating systems (Linux, Windows, macOS).  
- Pay-as-you-go pricing.  
- Elastic Load Balancing and Auto Scaling support.  

**Advantages**  
- Highly flexible (choose CPU, memory, storage).  
- Reliable and secure.  
- Easily integrates with other AWS services.  

**Disadvantages**  
- Costs can increase with long-term usage if not monitored.  
- Requires technical expertise to configure and secure properly.  

---

### 2. Amazon S3 (Simple Storage Service)  
**Features**  
- Object-based storage for files and backups.  
- Unlimited storage capacity.  
- Data versioning and lifecycle policies.  
- High availability and durability (99.999999999% durability).  

**Advantages**  
- Scalable and reliable.  
- Easy to integrate with apps and services.  
- Cost-effective storage with different storage classes.  

**Disadvantages**  
- Not suitable for block storage or databases.  
- Costs may rise with frequent data retrieval (from Glacier/IA tiers).  

---

### 3. Amazon VPC (Virtual Private Cloud)  
**Features**  
- Provides isolated virtual networks.  
- Supports subnets, route tables, NAT gateways, and VPN connections.  
- Control over inbound/outbound traffic via security groups and NACLs.  

**Advantages**  
- High level of security and network isolation.  
- Customizable network architecture.  
- Easy integration with on-premises networks.  

**Disadvantages**  
- More complex to configure compared to default networking.  
- Misconfiguration may lead to security issues.  

---

## Output  


<img width="1920" height="1200" alt="Screenshot 2025-09-15 141428" src="https://github.com/user-attachments/assets/6ddefdf9-d7dd-4912-82a1-9a04b050a343" />

---<img width="1920" height="1200" alt="Screenshot 2025-09-15 141906" src="https://github.com/user-attachments/assets/ba81c47e-8964-4b92-91fd-b1065e0209ad" />

<img width="1920" height="1200" alt="Screenshot 2025-09-15 142006" src="https://github.com/user-attachments/assets/d2227033-bf9a-40c7-8b3e-959752558376" />

<img width="1920" height="1200" alt="Screenshot 2025-09-15 142319" src="https://github.com/user-attachments/assets/07f338e9-5cfe-4f4b-9396-089a3efd0768" />
