# 🚀 Vagrant Apache Web Server Automation

## 📌 Overview
This project demonstrates how to **provision a Linux virtual machine** using **Vagrant** 
and automatically deploy an **Apache HTTP server** serving a static website template. 

It’s designed for learners to practice **Infrastructure as Code (IaC)**, **automation**, 
and basic **DevOps workflows**.

---

## 🛠️ Technologies Used
- [Vagrant](https://www.vagrantup.com/) – VM management tool
- [VirtualBox](https://www.virtualbox.org/) – Virtualization provider
- Linux (CentOS Stream 9)
- Apache HTTP Server
- Shell scripting for provisioning

---

## ⚙️ Features
- Creates a VM with **1024MB RAM**
- Configures **private** (`192.168.56.12`) and **public network**
- Installs and starts **Apache**
- Downloads and deploys a **Tooplate website template**
- Cleans up temporary files after provisioning
- Fully automated with a **Vagrant shell provisioner**

---

## 📁 Project Structure  
├── Vagrantfile # VM configuration and provisioning
└── README.md # Project documentation


---

## 🖥️ How It Works
1. Run `vagrant up` to create and configure the VM.
2. Vagrant provisions the VM automatically:
   - Installs Apache and required tools (`wget`, `unzip`)
   - Downloads and extracts the website template
   - Deploys it to `/var/www/html/`
3. VM is ready, Apache serving the website.
4. Temporary files are cleaned automatically.

---

## 🎯 Learning Goals
- Understand **VM provisioning** with Vagrant
- Learn **automated setup** of web servers
- Practice **IaC concepts** in a hands-on project
- Gain experience with **Linux commands** and basic shell scripting

---

## 👨‍💻 Author
**Yousef Rizk**  
Computer Science Student  
Aspiring DevOps Engineer  
DevOps Enthusiast
