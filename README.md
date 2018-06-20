# WebSploit
This is a virtual machine (VM) created by [Omar Santos](https://omarsantos.io) for different (Cybersecurity Ethical Hacking (Web Penetration Testing) training sessions](https://theartofhacking.org). The purpose of this VM is to have a lightweight (single VM) with a few web application penetration testing tools, as well as vulnerable applications.


## IMPORTANT!!!
This VM contains vulnerable software!
DO NOT connect to a production environment and use with caution!!!
 
 
## Tools included
- [BurpSuite Community Edition]
- [OWASP Zed Attack Proxy (ZAP)]
- [nmap](https://linux.die.net/man/1/nmap)
- [nikto](https://cirt.net/nikto2-docs)
- [sqlmap](https://github.com/sqlmapproject/sqlmap/wiki/Usage)
 
 
## Vulnerable Servers Included
- [Damn Vulnerable Web Application (DVWA)](http://www.dvwa.co.uk/)
- [WebGoat](https://www.owasp.org/index.php/Category:OWASP_WebGoat_Project)
- [Hackazon](https://github.com/rapid7/hackazon)
 
### All of the vulnerable servers are running in Docker containers

All containers are configured to start at boot time. 
To obtain the status of each docker container use the `sudo docker ps` command.

If they are not started use the following commands to start each container:

```
sudo docker start dvwa
sudo docker start webgoat
sudo docker start hackazon
```
