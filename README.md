# Ansible Project: Install Nginx and Deploy Static Website

# Project Overview
1.Installing Nginx on remote servers.
2.Starting and enabling the Nginx service.
3.Deploying a static web page to the server.

---

# We are managing two environments:
1.Development Server (devserver).
2.Production Server (prdserver).

---


# Prerequisites
1.Ubuntu EC2 Instances (or any Linux server).
2.Ansible installed on the control machine.
3.SSH access with private key.

---

# Playbooks Description
1.install_nginx.yml(Installs and starts the Nginx service on development servers (devserver)).
2.deploy.yml(Deploys a static index.html file to the production server (prdserver) inside /var/www/html/).

---

# How to Run
```
ansible-playbook install_nginx.yml
```
```
ansible-playbook deploy.yml
```

---


# Screenshots
## 📸 Screenshot: Playbook running in terminal
(https://github.com/user-attachments/assets/1e513c60-2079-4f64-a0b5-1e1a8b9e8b84)

## 📸 Screenshot: Default "Welcome to Nginx" Page
(https://github.com/user-attachments/assets/863df5e4-c5c8-4742-a1e1-ad15f23f9236)

## 📸 Screenrecording: Static Web Page (Deployed)
(https://github.com/user-attachments/assets/f09b60a2-2707-485a-b110-c84b0965bc77)

---

# Conclusion
This project shows how easy and powerful Ansible is for:
1.Installing packages.
2.Managing services.
3.Deploying files remotely.





