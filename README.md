# WebSploit
This is a virtual machine (VM) created by [Omar Santos](https://omarsantos.io) for different (Cybersecurity Ethical Hacking (Web Penetration Testing) training sessions](https://theartofhacking.org). The purpose of this VM is to have a lightweight (single VM) with a few web application penetration testing tools, as well as vulnerable applications.


## IMPORTANT!!!
This VM contains vulnerable software!
DO NOT connect to a production environment and use with caution!!!

## Getting Started

1. Download [VirtualBox](https://www.virtualbox.org). This is an all-in-one VM created and tested in [VirtualBox](https://www.virtualbox.org).  VirtualBox is a general-purpose full virtualizer for x86 hardware, targeted at server, desktop and embedded use. For a thorough introduction to virtualization and VirtualBox, please refer to [the online version of the VirtualBox User Manual's first chapter](https://www.virtualbox.org/manual/ch01.html).

2. **Download the .ova file from http://h4cker.org/websploit** and import it in VirtualBox. [Click here](https://www.virtualbox.org/manual/ch01.html#ovf) for detailed instructions on how to import a VM in VirtualBox.

 
## Just a Kali Linux VM with Vulnerable Applications
This is an all-in-one Kali + Vulnerable Applications standalone VM designed for you to practice your skills in a safe environment.
 
 
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

If for some reason docker does not start at bootup use the following command to start it:
```
service docker start
```
