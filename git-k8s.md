# 📘 Project-Nautilus-KodeKloud-Engineers

This repository documents my journey through the **KodeKloud Initiative Program**, where I am working as a **System Administrator (DevOps Engineer in Training)**. My chosen tools for the program are **Git** and **Kubernetes**, and this repo serves as a log of all related tasks completed during the training.

## 🧭 Program Details

- **Program**: KodeKloud Initiative
- **Role**: System Administrator
- **Focus Tools**: Git, Kubernetes
- **Start Date**: Apr 2020
- **Location**: Remote (India)

---
![image](https://github.com/user-attachments/assets/82bef26a-dfbb-4033-b0c9-2ac17226c57a)
## 🛠️ Daily Task Log

### Day 1 - [Git]
**Task**: The Nautilus development team has provided requirements to the DevOps team for a new application development project, specifically requesting the establishment of a Git repository. Follow the instructions below to create the Git repository on the Storage server in the Stratos DC:



Utilize yum to install the git package on the Storage Server.


Create a bare repository named /opt/media.git (ensure exact name usage). 
**Commands/Tools**: `git init`, `.gitignore`, README setup  
**Learning**: Understood repo structure & Git basics  
**solution**🧩 Steps Performed
SSH Access
ssh natasha@ststor01.stratos.xfusioncorp.com
# Password: Bl@kW
**Install Git**:
sudo yum install git -y:
**Create Bare Repository**:
sudo git init --bare /opt/media.git:
**Verify Repository**:
ls /opt/media.git:

**🖥️ Server Info Table (for reference)

Server Name	IP Address	Hostname	User	Password	Purpose
ststor01	172.16.238.15	ststor01.stratos.xfusioncorp.com	natasha	Bl@kW	Nautilus Storage Server




---

### Day 1 - [K8S]
**Task**: The Nautilus DevOps team is diving into Kubernetes for application management. One team member has a task to create a pod according to the details below:


Create a pod named pod-httpd using the httpd image with the latest tag. Ensure to specify the tag as httpd:latest.

Set the app label to httpd_app, and name the container as httpd-container.

Note: The kubectl utility on jump_host is configured to operate with the Kubernetes cluster. 
**Commands/Tools**: `kubectl`, `pod.yaml`  
**Learning**: Pod lifecycle, YAML syntax  

---

(Continue daily...)

---

## 📌 Notes
- I will update this document daily as I complete new tasks.
- This serves as a reflection of progress and a knowledge base for revision.

