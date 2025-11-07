# 🌐 Single Zone VPC Webserver

## Architecture
- Custom VPC (10.0.0.0/16)
- Public Subnet with Internet Gateway
- Apache Webserver on EC2
- Security Groups for HTTP/SSH

## Screenshots
![VPC Created](screenshots/vpc-created.png)
![Subnet Configured](screenshots/subnet-configured.png)
![Security Groups](screenshots/security-groups.png)
![Website Running](screenshots/website-running.png)

## Deployment
```bashTechnologies Used

· AWS VPC, EC2, IAM
· Bash Scripting
· Apache HTTP Server

Created by

Mukul - Cloud & DevOps Enthusiast
# Create VPC and launch webserver
chmod +x scripts/setup-vpc.sh
./scripts/setup-vpc.sh
