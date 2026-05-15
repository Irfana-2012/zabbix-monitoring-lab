# Enterprise Monitoring & Incident Management 

## Overview

This project demonstrates a real-world infrastructure monitoring and incident management workflow using:

- AWS EC2
- Ubuntu Linux
- Zabbix Server
- Zabbix Agent 2
- Jira Cloud
- Oracle VirtualBox

The environment monitors Linux infrastructure metrics in real time and simulates operational incident workflows commonly used in DevOps, SRE, NOC, and Cloud Support environments.

---

# Zabbix monitoring and Jira Architecture Diagram
<img width="1536" height="1024" alt="zabbix architecture diagram" src="https://github.com/user-attachments/assets/6fbd029c-b607-4263-b3ba-6bc856db9048" />


# Technologies Used

| Technology | Purpose |
|---|---|
| AWS EC2 | Cloud-hosted monitoring server |
| Ubuntu Linux | Monitored infrastructure host |
| Zabbix Server | Infrastructure monitoring platform |
| Zabbix Agent 2 | Linux host monitoring |
| Apache2 | Zabbix web frontend |
| MariaDB | Backend database |
| Jira Cloud | Incident management & ticketing |
| Oracle VirtualBox | Virtualized lab environment |

---

# Infrastructure Components

## AWS EC2 Zabbix Server

Configured:

- Zabbix Server
- Apache2 Web Server
- MariaDB Database
- Monitoring Dashboard
- Trigger & Alert System
<img width="1366" height="768" alt="zabbix-server" src="https://github.com/user-attachments/assets/11d37148-f1b0-4143-88c1-53befc8e9ba3" />
<img width="1366" height="768" alt="zabbix-server-vpc" src="https://github.com/user-attachments/assets/db8bcd86-73c9-4e85-9d2e-b4b60364aaac" />
<img width="1366" height="768" alt="zabbix-installation" src="https://github.com/user-attachments/assets/e13c3e93-a9b2-4fac-9064-92c81042d49b" />



## Ubuntu Linux VM

Configured:

- Zabbix Agent 2
- Host Monitoring
- CPU Monitoring
- Memory Monitoring
- Disk Monitoring
- Network Monitoring
<img width="1280" height="800" alt="zabbix-agent-running" src="https://github.com/user-attachments/assets/f4946f21-904f-4207-b03c-76704d80972d" />
<img width="1366" height="768" alt="ubuntu-vm" src="https://github.com/user-attachments/assets/36bf861e-b324-483b-9b54-ae78c71bb83e" />


## Jira Cloud

Configured:

- Incident Ticketing
- Alert Tracking
- Operational Workflow Simulation
- Infrastructure Incident Management

---

# Monitoring Features

## Infrastructure Monitoring

- Real-time CPU monitoring
- Memory utilization monitoring
- Disk usage monitoring
- Network monitoring
- Linux host availability monitoring
- Performance graph analysis
<img width="1366" height="768" alt="monitoring (2)" src="https://github.com/user-attachments/assets/9b3a0132-c865-4aa3-9d65-6dc855041a26" />
<img width="1366" height="768" alt="monitoring" src="https://github.com/user-attachments/assets/86766857-ba5b-4b84-95c4-31a344ae10a3" />


## Alerting & Monitoring

- Trigger-based monitoring
- Host availability checks
- Threshold-based alerts
- Monitoring dashboards
- Real-time infrastructure metrics
<img width="1536" height="1024" alt="jira dashboard" src="https://github.com/user-attachments/assets/dd3f8a46-2d01-476e-a885-2ec6c5744d0c" />

## Incident Management

- Jira incident creation
- Alert tracking workflow
- Monitoring issue management
- Operational troubleshooting simulation
<img width="1536" height="1024" alt="incident management" src="https://github.com/user-attachments/assets/66b92bd7-d7e9-44d5-b624-9b161313a9fd" />

---

# Enterprise Workflow

```text
Ubuntu Linux VM
        ↓
Zabbix Agent 2
        ↓
AWS EC2 Zabbix Server
        ↓
Monitoring Triggers & Alerts
        ↓
Jira Incident Ticket
        ↓
Investigation & Resolution Workflow
```

---

# Network Configuration

## AWS Cloud Layer

- EC2 Ubuntu Server
- Security Group Configuration
- Port 10050 Monitoring Access
- Zabbix Web Frontend

## Local VirtualBox Environment

- Ubuntu Linux VM
- Zabbix Agent Connectivity
- NAT / Port Forwarding Configuration
- Internal Monitoring Setup

---

# Zabbix Configuration

Implemented:

- Host monitoring
- Linux by Zabbix Agent template
- Availability monitoring
- Agent communication
- Performance graphs
- Dashboard monitoring

---

# Jira Configuration

Configured:

- Jira project
- Monitoring incident tickets
- Operational workflow simulation
- Infrastructure issue tracking

---

# Screenshots

## Zabbix

Add screenshots for:

- Zabbix Dashboard
- Host Availability
- CPU Monitoring Graph
- Memory Monitoring Graph
- Latest Data
- Monitoring Alerts
- Ubuntu Agent Status

## Jira

Add screenshots for:

- Jira Dashboard
- Monitoring Incident Ticket
- Alert Tracking Task

---

# Skills Demonstrated

## Cloud & Infrastructure

- AWS EC2 Administration
- Linux Administration
- Infrastructure Monitoring
- Network Troubleshooting
- Cloud-Based Monitoring Deployment

## Monitoring & Operations

- Zabbix Installation & Configuration
- Agent-Based Monitoring
- Infrastructure Alerting
- Monitoring Dashboard Analysis
- Performance Monitoring

## Incident Management

- Jira Ticketing
- Operational Workflow Simulation
- Infrastructure Incident Tracking
- Troubleshooting Process

## Virtualization

- Oracle VirtualBox
- NAT Networking
- Port Forwarding
- VM Connectivity Troubleshooting

---

# Challenges Solved

- Zabbix agent communication issues
- VirtualBox NAT networking problems
- Port forwarding configuration
- AWS EC2 connectivity troubleshooting
- Zabbix frontend setup issues
- Monitoring host availability problems
---

# Project Status

## Fully Functional Monitoring & Incident Management 

Successfully implemented:

- AWS-hosted Zabbix monitoring server
- Ubuntu monitored Linux host
- Active Zabbix Agent 2 monitoring
- Real-time infrastructure monitoring
- Jira-based incident management workflow
- Infrastructure alert tracking

---
