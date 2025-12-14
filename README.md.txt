# Azure Load Balancer Project

This project demonstrates the implementation of an Azure Standard Load Balancer
to distribute HTTP traffic across two Ubuntu virtual machines.

## Technologies Used
- Microsoft Azure
- Azure Virtual Machines
- Azure Load Balancer
- Apache Web Server
- Ubuntu Linux

## Architecture
- Two Ubuntu Virtual Machines (webvm1, webvm2)
- Standard Public Load Balancer
- Backend Pool with both VMs
- Health Probe on Port 80

## Result
When accessing the Load Balancer public IP, traffic is distributed between:
- Hello from VM1
- Hello from VM2

## Author
Aryan Jamwal  

