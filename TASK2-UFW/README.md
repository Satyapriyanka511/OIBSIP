# Task 2: Basic Firewall Configuration with UFW

## Objective
The objective of this task is to configure a basic firewall using UFW (Uncomplicated Firewall) on Kali Linux to allow SSH traffic and block HTTP traffic.

## Tools Used
- UFW (Uncomplicated Firewall)
- Kali Linux

## Steps / Commands
1. Enabled the UFW firewall.
2. Allowed SSH traffic using port 22.
3. Denied HTTP traffic using port 80.
4. Verified firewall rules using the ufw status command.

## Results
- SSH (port 22) is allowed.
- HTTP (port 80) is denied.
- Firewall is active and running.

## Security Explanation
Allowing only required services and blocking unnecessary ports helps reduce the attack surface of the system. Firewalls play a critical role in preventing unauthorized access and improving overall network security.
