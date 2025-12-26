📌 Project Title

Ranthambhore Safari Website Deployment on AWS


📖 Project Description

This project demonstrates how to deploy a static website on AWS EC2 using Nginx Web Server and connect it with a custom domain using AWS Route 53.

The website Ranthambhore Safari is live and accessible via a custom subdomain, showcasing real-world cloud deployment and DevOps fundamentals.



🌐 Live Website

🔗 http://ranthambhore.priyank-learning.xyz



🛠️ Technologies Used

AWS EC2 (t3.micro)

Amazon Route 53 (DNS Management)

Nginx Web Server

Linux (Ubuntu)




🏗️ Architecture Overview
User Browser
     ↓
Route 53 (DNS)
     ↓
EC2 Public IP
     ↓
Nginx Web Server
     ↓
Website Content



⚙️ Steps Performed

1️⃣ EC2 Instance Setup
Launched EC2 instance in eu-north-1 (Stockholm)
Opened ports 80 (HTTP) and 22 (SSH)

Installed Nginx

sudo apt update
sudo apt install nginx -y







2️⃣ Website Deployment

Uploaded website files to:
/var/www/html/
Verified website using EC2 public IP



Route 53 Configuration

Created Hosted Zone: priyank-learning.xyz
Added A Record:
ranthambhore.priyank-learning.xyz
Pointed to EC2 Public IP
DNS propagation verified successfully




