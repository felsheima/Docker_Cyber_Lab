# Docker Cybersecurity Lab — Kali + Metasploitable

## Overview
This project demonstrates the setup of a controlled cybersecurity lab using Docker
to practice network reconnaissance, service enumeration, and vulnerability assessment.

The lab simulates an attacker (Kali Linux) and a vulnerable target (Metasploitable)
connected through a custom Docker network.

## Objectives
- Build an isolated cyber range using containers
- Perform host discovery and network scanning
- Identify open ports and running services
- Detect operating system and service versions
- Run vulnerability detection scripts
- Analyze attack surface

## Lab Architecture
Attacker: Kali Linux container  
Target: Metasploitable container  
Network: Docker bridge network (lab_network)

## Tools Used
- Docker
- Kali Linux
- Metasploitable
- Nmap

## Setup Instructions

### Create network
```bash
docker network create lab_network