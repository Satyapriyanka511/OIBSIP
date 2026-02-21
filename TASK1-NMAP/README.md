# Task 1: Basic Network Scanning with Nmap

## Objective
The objective of this task is to perform a basic network scan using Nmap on a local system (Kali Linux) to identify open ports and running services.

## Tools Used
- Nmap
- Kali Linux (VirtualBox)

## Steps / Commands
1. Verified Nmap installation using:
   
   nmap --version
   
3. Performed a basic scan on localhost:

   nmap localhost

4. Performed a service version scan on localhost:

   nmap -sV localhost

5. Saved the scan output to a text file for documentation.

## Results
The Nmap scan results show that:
- The host (127.0.0.1) is up and reachable.
- All 1000 scanned TCP ports are closed.
- No open ports or running network services were detected on the system.

## Security Explanation
Closed ports indicate that no unnecessary services are exposed to the network. This reduces the attack surface of the system and improves security. Regular network scanning helps administrators verify that only required services are running and that the system is properly secured.
