# 🚀 AWS Secure Web Deployment with Security Hardening

📌 Project Overview
This project demonstrates deploying a secure web application using AWS EC2 and implementing multiple layers of security.

☁️ Technologies Used
- AWS EC2
- Apache Web Server
- Linux (Amazon Linux 2023)
- Fail2Ban
- Security Groups

🔧 Features
- Hosted a live website on AWS
- Configured firewall using Security Groups
- Restricted SSH access (My IP only)
- Disabled root login
- Implemented Fail2Ban for intrusion prevention

 🪜 Steps Performed
1. Launched EC2 instance
2. Connected via SSH
3. Installed Apache server
4. Hosted website
5. Applied security hardening
6. Configured Fail2Ban

⚠️ Errors Faced & Fixes
- SSH connection issues → Fixed by correct key path and permissions
- Fail2Ban jail = 0 → Enabled sshd configuration
- Fail2Ban service failed → Fixed syntax errors in config file

📸 Screenshots
<img width="1467" height="596" alt="instance" src="https://github.com/user-attachments/assets/f73308a8-c976-4a83-9096-0497a2c010c2" />
<img width="1453" height="746" alt="security working" src="https://github.com/user-attachments/assets/62d01fc9-8eef-4a1b-a596-c97ed26b5c62" />
<img width="1469" height="732" alt="(MySecureServer)" src="https://github.com/user-attachments/assets/fa36066e-5300-4d28-b0fe-2d2bdf401014" />
<img width="1003" height="739" alt="fail2ban-working" src="https://github.com/user-attachments/assets/ffdd10bf-d934-42fb-bc0e-8f5e1718c73f" />

💼 Resume Highlight
Deployed a secure web application on AWS EC2 with firewall rules, SSH hardening, and intrusion prevention using Fail2Ban.

