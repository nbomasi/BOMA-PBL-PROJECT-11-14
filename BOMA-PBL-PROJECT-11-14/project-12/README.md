## PBL-Project-12

# ANSIBLE REFACTORING AND STATIC ASSIGNMENTS (IMPORTS AND ROLES)

AANSIBLE REFACTORING, ASSIGNMENTS & IMPORTS

Note: This project is an enhancement to project 11, I will maintain the same repo (ansible-config-mgt). This project will introduce us to the following concept: Refactoring, assignment, imports, and role. this means that all must be up and running well before I can implement project 10.

Keywords:

IMPORT: A functionality that allows ansible playbook code to be reused. It also make codes more organised.

REFACTORING: is a general term in computer programming. It means making changes to the source code without changing expected behaviour of the software. The main idea of refactoring is to enhance code readability, increase maintainability and extensibility, reduce complexity, add proper comments without affecting the logic.

## Cloud Infracture for the Project

* Cloud Platform: AWS

* OS: 5 Red Hat Enterprise Linux 8; 3 Ubuntu 20.04

**Server Applications:**

* Webserver (Red Hat Enterprise Linux 8): 2 Apache2

* Load balancer Server (Ubuntu 20.04): NGINX load balancer

* Database server (Ubuntu 20.04): MYSQL

* Storage Server (Red Hat Enterprise Linux 8): NFS server

* CI/CD Server (Ubuntu 20.04): Jenkins-Ansible

* UAT Webserver (Red Hat Enterprise Linux 8):