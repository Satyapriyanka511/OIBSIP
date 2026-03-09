# Task 7: Vulnerability Scanning with Nikto

## Objective

The objective of this task is to perform vulnerability scanning on a web server using the Nikto tool and identify possible security vulnerabilities.

## Tool Used

Nikto – an open-source web server vulnerability scanner used to detect security issues such as outdated server software, misconfigurations, and dangerous files.

## Environment

* Operating System: Kali Linux
* Tool: Nikto

## Target Website

http://testphp.vulnweb.com

## Commands Used

Install Nikto:

sudo apt update
sudo apt install nikto

Check Nikto installation:

nikto -h

Run vulnerability scan:

nikto -h http://testphp.vulnweb.com

Save scan results to a file:

nikto -h http://testphp.vulnweb.com -o nikto_scan_results.txt

View saved results:

cat nikto_scan_results.txt

## Results

The Nikto scan analyzed the target web server and detected several potential security issues such as missing security headers and possible server configuration weaknesses.

## Conclusion

Nikto helps security professionals identify vulnerabilities in web servers. Regular vulnerability scanning helps organizations detect and fix security issues before attackers exploit them.
