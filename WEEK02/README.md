Week 2 — Enterprise Infrastructure Planning
Project Overview

This project focuses on designing and planning the enterprise IT infrastructure of EJQQ Solution Inc, a newly established software development company with 20 employees.

The company currently has no computers, servers, networking equipment, Internet infrastructure, or security policies. Therefore, a complete IT infrastructure plan was developed to identify the required hardware, software, networking equipment, network topology, system administration roles, security recommendations, backup strategy, and future expansion requirements.

The project also includes an enterprise network diagram created using Draw.io to illustrate how the company's Internet connection, networking devices, server, printer, wireless access points, and departmental computers are connected.

Learning Objectives

After completing this project, I was able to:

Identify the hardware requirements of a startup organization.
Identify appropriate enterprise software for different departments.
Design a basic enterprise network infrastructure.
Create an enterprise network topology using Draw.io.
Understand the roles and responsibilities of System Administrators.
Recommend appropriate Internet, server, backup, and security solutions.
Develop a password and security policy.
Plan an infrastructure that can support future company expansion.
Document IT infrastructure requirements professionally.
Understand how different IT components work together to support business operations.
Company Scenario

Company Name: EJQQ Solution Inc

Business Type: Software Development Company

Location: 084 Brgy kungpurungpung, EJQQ Solution Inc, National Highway, Bay, Laguna, Philippines 

Number of Employees: 20

EJQQ Solution Inc is a newly established software development company that provides software development, web application development, database solutions, IT consulting, and technical support services.

The company operates on a single office floor and currently has no computers, servers, networking equipment, Internet infrastructure, or security policies.

The organization requires a complete IT infrastructure to support its employees and business operations.
Department Distribution
| Department             | Employees | Main Function                            |
| ---------------------- | --------: | ---------------------------------------- |
| Information Technology |         5 | Software development and IT support      |
| Human Resources        |         4 | Recruitment and employee administration  |
| Finance                |         5 | Accounting and financial operations      |
| Sales                  |         6 | Sales, marketing, and customer relations |
| **Total**              |    **20** |                                          |

Hardware Inventory Summary

The following hardware was selected to support the company's 20 employees and enterprise infrastructure.
| Hardware               | Quantity | Purpose                               |
| ---------------------- | -------: | ------------------------------------- |
| Desktop Computers      |       20 | Employee workstations                 |
| Laptop Computers       |        5 | IT administration and mobile work     |
| Server                 |        1 | Centralized services and file sharing |
| Router                 |        1 | Internet and network routing          |
| Managed Switch         |        1 | Central network connectivity          |
| Network Printers       |        2 | Shared printing                       |
| UPS                    |        3 | Power protection                      |
| Wireless Access Points |        2 | Wireless connectivity                 |
| NAS Storage            |        1 | Centralized storage and backup        |
| External Backup Drives |        2 | Offline backup                        |
| Monitors               |       20 | Employee displays                     |
The hardware was selected based on the company's current size while allowing the infrastructure to support future expansion.

Software Inventory Summary

The following software will be deployed throughout the organization.
| Software           | Purpose                           |
| ------------------ | --------------------------------- |
| Windows 11 Pro     | Employee operating system         |
| Ubuntu Server LTS  | Server operating system           |
| Microsoft Office   | Business productivity             |
| Visual Studio Code | Software development              |
| Git                | Version control                   |
| GitHub Desktop     | Git repository management         |
| VirtualBox         | Virtual machine management        |
| Google Chrome      | Web browsing and web applications |
| Microsoft Defender | Endpoint security                 |
| AnyDesk            | Remote IT support                 |
| 7-Zip              | File compression and extraction   |
Software selection was based on the company's software development requirements, productivity needs, security requirements, and system administration activities.

Embedded Network Diagram
Enterprise Network Topology

The proposed network uses an extended star topology, also commonly described as a hierarchical star topology.

The core managed switch acts as the central connection point for the internal network.

The basic network structure is:

                         INTERNET
                             │
                             ▼
                        ISP MODEM
                             │
                             ▼
                          ROUTER
                             │
                             ▼
                         FIREWALL
                             │
                             ▼
                     CORE MANAGED SWITCH
                             │
             ┌───────────────┼────────────────┐
             │               │                │
             ▼               ▼                ▼
          SERVER          PRINTER       WIRELESS APs
                                             │
                           ┌─────────────────┼─────────────────┐
                           │                 │                 │
                           ▼                 ▼                 ▼
                      IT DEPARTMENT     HR DEPARTMENT    FINANCE DEPARTMENT
                         5 PCs             4 PCs             5 PCs
                                                              
                                             │
                                             ▼
                                      SALES DEPARTMENT
                                           6 PCs

                                           Network Components
Internet
ISP Modem
Router
Firewall
Core Managed Switch
Patch Panel
Server
Network Printers
Two Wireless Access Points
IT Department
HR Department
Finance Department
Sales Department
Topology Description

The network follows an extended star/hierarchical star topology because the core managed switch functions as the central connection point for the organization's network devices and departments.

This topology was selected because it is relatively easy to manage, troubleshoot, and expand. If an individual workstation or cable fails, the failure generally affects only that device rather than the entire network.

The network also provides a clear structure:
Internet
   ↓
ISP Modem
   ↓
Router
   ↓
Firewall
   ↓
Core Switch
   ↓
Departments / Server / Printers / Wireless APs

Technologies Used

The following technologies and tools were used to develop the infrastructure plan:
| Technology / Tool  | Usage                            |
| ------------------ | -------------------------------- |
| Draw.io            | Network topology design          |
| Windows 11 Pro     | Desktop operating system         |
| Ubuntu Server LTS  | Server operating system          |
| Microsoft Office   | Business productivity            |
| Visual Studio Code | Software development             |
| Git                | Version control                  |
| GitHub             | Project repository and portfolio |
| GitHub Desktop     | Graphical Git management         |
| VirtualBox         | Virtual machine management       |
| Google Chrome      | Web access                       |
| Microsoft Defender | Endpoint security                |
| AnyDesk            | Remote technical support         |
| 7-Zip              | File compression                 |

Challenges Encountered

One of the main challenges encountered during the project was determining the appropriate hardware and network equipment for a 20-person software development company.

It was necessary to consider the number of employees, departments, expected workloads, network connectivity, storage requirements, security, and future expansion before selecting the equipment.

Another challenging part was designing the enterprise network topology. The network needed to show how the Internet, ISP modem, router, firewall, switch, server, printers, wireless access points, and departmental computers would connect.

Creating the network diagram in Draw.io helped make the proposed infrastructure easier to understand and provided a visual representation of how the different components communicate.

Another challenge was selecting appropriate software for different business requirements. The company requires both general productivity software and specialized development tools, so the software inventory had to accommodate both business and technical users.

Reflection

This project helped me understand that planning an IT infrastructure requires more than simply choosing computers and connecting them to the Internet.

I learned that a System Administrator must first understand the organization's business requirements, number of employees, departments, applications, network requirements, security needs, and future growth before designing the infrastructure.

One of the most important things I learned was the importance of proper network planning. The network diagram helped me understand how different devices such as routers, firewalls, switches, servers, printers, and wireless access points work together.

I also learned that security and backup planning should be considered from the beginning rather than added after the infrastructure has already been deployed. A company depends on its data and systems, so protecting information from unauthorized access, malware, hardware failure, and other risks is essential.

The project also improved my understanding of System Administrator responsibilities. A System Administrator must be able to manage hardware, software, networks, servers, security, backups, and technical support.

Overall, this project gave me a better understanding of how enterprise infrastructure is planned before actual deployment. It also improved my ability to document technical decisions and communicate an IT infrastructure design clearly.

References
ITEP 414 – System Administration and Maintenance, Week 2 Module
Draw.io — Network diagramming and visualization tool
Microsoft — Windows 11 Pro documentation
Ubuntu — Ubuntu Server documentation
Git — Version control documentation
GitHub — Repository and collaboration documentation
Microsoft Defender — Endpoint security documentation
VirtualBox — Virtualization software documentation