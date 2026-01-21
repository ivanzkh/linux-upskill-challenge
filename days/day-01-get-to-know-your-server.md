
# Day 1. Get to know your server

## Objective

Establish SSH access to the server and collect baseline system information.

## Environment

Cloud provider: Azure
OS: Ubuntu Server LTS
Access method: SSH using PEM key
User: azureuser

## SSH connection

Command used to access the server:

ssh -i Subscriber_key.pem azureuser@20.39.129.68

Notes:
Host key accepted on first connection.
Session ended using exit.

## Commands executed


OS and kernel information:
uname -a
uptime

Hardware information:
lscpu
lsblk

Memory and CPU usage:
free -h
top

Disk usage:
df -h

Network information:
ip address
ip route

## Results

Terminal output was not saved for Day 1.
This day focused on common Linux system inspection commands.

## Key takeaways

SSH is the standard method for remote Linux administration.
free -h, df -h, and top provide fast system health checks.
ip address replaces legacy networking tools like ifconfig.
