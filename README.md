cat > README.md <<'EOF'
# AWS Cloud Hosting Internship Project

## Project Overview
This project demonstrates practical implementation of AWS cloud infrastructure and website hosting using Amazon EC2 and Apache HTTP Server.

## Internship Objectives
1. Learn IAM Users, Groups, Roles, Policies and Permissions.
2. Understand AWS Security and Least Privilege Principle.
3. Launch and configure an Amazon EC2 instance.
4. Configure Security Groups and connect to EC2.
5. Install a web server and deploy a basic HTML website.

## Technologies Used
- AWS IAM
- Amazon EC2
- Amazon Linux
- Security Groups
- Apache HTTP Server
- HTML
- Git and GitHub

## Implementation
### IAM Configuration
Worked with IAM users, groups, roles, policies and permissions.

### AWS Security
Understood AWS security and the principle of least privilege.

### EC2 Configuration
Launched and configured an Amazon Linux EC2 instance.

### Security Group
Configured SSH port 22 and HTTP port 80.

### Apache Installation
Installed Apache using:
sudo dnf install httpd -y

Started Apache:
sudo systemctl start httpd

Enabled Apache:
sudo systemctl enable httpd

### Website Deployment
Created an HTML website at:
/var/www/html/index.html

Verified the website using:
curl http://localhost

Accessed the website through the EC2 Public IPv4 address.

## Project Outcome
Successfully deployed a basic HTML website on Amazon EC2 using Apache HTTP Server.

## Learning Outcomes
- AWS Identity and Access Management
- Cloud Security
- EC2 Management
- Linux Administration
- Apache Web Server
- Website Hosting
- Git and GitHub

## Author
Tejaswini Bachhav

## Status
Completed
EOF

