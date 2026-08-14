# Week 3 — Enterprise Server Deployment and Operating System Installation

## Project Overview

This project focuses on deploying an Ubuntu Server virtual machine for ABC Startup Solutions. The server will provide the foundation for future file sharing, remote administration, database hosting, web hosting, and internal services.

## Learning Objectives

* Understand the role of operating systems in enterprise environments.
* Differentiate BIOS and UEFI.
* Understand the Linux boot process.
* Install Ubuntu Server.
* Configure a Linux server.
* Enable SSH.
* Verify server functionality.
* Compare enterprise operating systems.
* Produce professional technical documentation.

## Virtual Machine Specifications

| Component | Specification        |
| --------- | -------------------- |
| Name      | Ubuntu-Server-Week03 |
| RAM       | 4 GB                 |
| CPU       | 2 Virtual Processors |
| Storage   | 40 GB                |
| Network   | NAT                  |
| Hostname  | server01             |
| OS        | Ubuntu Server LTS    |

## Installation Summary

Ubuntu Server LTS was installed inside a virtual machine. The installation included English language selection, keyboard configuration, DHCP networking, hostname configuration, user creation, guided disk partitioning, and OpenSSH Server installation.

## Configuration Summary

* Hostname: `server01`
* Network: DHCP
* Storage: 40 GB
* SSH: OpenSSH Server
* Administrative user: Created during installation
* Additional packages: None unless required

## Verification Results

| Verification | Command                                   | Result         |
| ------------ | ----------------------------------------- | -------------- |
| Hostname     | `hostname`                                | `server01`     |
| IP Address   | `ip addr`                                 | Verified       |
| Internet     | `ping -c 4 google.com`                    | Verified       |
| Updates      | `sudo apt update` / `sudo apt upgrade -y` | Verified       |
| SSH          | `systemctl status ssh`                    | Active/running |

Replace the results with the actual results from the VM.

## BIOS vs UEFI Highlights

BIOS is the traditional firmware technology used by older computers. UEFI is its modern replacement and provides improved support for GPT, large storage devices, modern boot management, and security features such as Secure Boot.

## Boot Process

```text
Power On
↓
BIOS / UEFI Initialization
↓
Boot Device Detection
↓
GRUB
↓
Linux Kernel
↓
init / systemd
↓
Services Start
↓
Login Prompt
```

## Challenges Encountered

The main challenges involved configuring the virtual machine correctly, understanding the Ubuntu installation process, verifying network connectivity, and understanding how the Linux boot process works.

## Reflection

Completing this project improved my understanding of how operating systems serve as the foundation of an enterprise IT infrastructure. I learned that installing an operating system is only one part of server deployment. A system administrator must also configure the network, hostname, user accounts, storage, remote administration, updates, and security.

Installing Ubuntu Server in a virtual machine allowed me to practice server deployment without requiring physical server hardware. I also learned how to use commands such as `hostname`, `ip addr`, `ping`, `sudo apt update`, `sudo apt upgrade -y`, and `systemctl status ssh` to verify the condition of a Linux server.

The BIOS and UEFI comparison helped me understand how computers start before the operating system loads. I learned why UEFI is important in modern systems and how it differs from traditional BIOS.

The most challenging part was understanding how the different stages of the boot process connect together. Creating the flowchart helped make the process easier to understand because it showed the sequence from powering on the computer through firmware initialization, bootloader execution, kernel loading, system initialization, service startup, and finally the login prompt.

This project will help me become a better System Administrator because it provided practical experience in installing, configuring, testing, and documenting a server. I also learned the importance of creating documentation that another administrator can follow. Good documentation reduces errors and makes future troubleshooting and maintenance easier.

Overall, the project demonstrated that server administration requires technical knowledge, careful planning, verification, security awareness, and documentation. These skills will be useful when managing real enterprise systems in the future.

## References

* ITEP 414 – System Administration and Maintenance, Week 3 Module
* Ubuntu Server documentation
* Microsoft Windows Server documentation
* Rocky Linux documentation
