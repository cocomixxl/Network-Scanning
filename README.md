# Network-Scanning


## Objective

Verify the installation and version of nmap on our system, run a scan to discover information on a target, and output our scan results to a file for further assessment


### Skills Learned

- Create a Cloud Monitoring account that has two Google Cloud projects.
- Monitor across both projects from the single Cloud Monitoring account.

### Tools Used
- Nmap
- Xfce Ubuntu


## Steps
### Task #1
Task Goal verify the installation and version of Nmap using the terminal
![image](https://github.com/user-attachments/assets/6c2da612-b0c3-49d9-b3bb-ff8730c83734)

###Key Takeaways
- Verifying a successful installation of Nmap confins that it is nady for use on the
- Verifying the Nimap version on your system is important for compatibility rposes in order to know the features available for you to use

### Task #2
Access the Help feature and Man Page for Nmap
![image](https://github.com/user-attachments/assets/0602a0b1-9374-4fde-9f16-b2611d8f4b8c)
![image](https://github.com/user-attachments/assets/23449dde-8b7b-41d9-b49b-3562beebd56d)
![image](https://github.com/user-attachments/assets/6ed434bb-765a-459a-ade8-123f73dc3dde)
or just nmap then clear to clear the screen
type man nmap
![image](https://github.com/user-attachments/assets/ddd9bf9e-8a01-4d43-99cc-cdae0d8ccbb6)


## Key Takeaways
- Reference the map help feature or man page when you need to recall information to use when scanning scanning
- Nmap man page, also known as the Nimap Reference Guide, is a detailed manual into sections that has additional scanning information and examples
- Use as ressourses
### Task #3
Perform a Basic Nmap Scan
![image](https://github.com/user-attachments/assets/d498ee07-c19d-4971-8f03-a8be5a362c25)
![image](https://github.com/user-attachments/assets/95cbd279-9101-4a6b-b6ea-17a150c18577)
![image](https://github.com/user-attachments/assets/f7852a6f-3df3-4826-8bd5-0af5a6f20792)
![image](https://github.com/user-attachments/assets/40908db1-218f-4953-8d6d-db85cff035de)
### Key Takeaways:
Nmap should be performed with care on authorized targets
A basic ping scan identifies if a target is active and detects what ports are open
and services are running,
Nmap scanning allows you to monitor your network for potential vulnerabilities.
##practice test
Perform a scan on your Rhyme host IP address using Nmap (referencing the man page as needed) and note open ports and running services on your host.
![image](https://github.com/user-attachments/assets/2893b679-a142-4396-8e86-ed950239ca8d)
The scan identified two open ports:
- 5901/tcp: Used by VNC (Virtual Network Computing), a remote desktop protocol.

- 6901/tcp: Used by Jetstream, a service related to remote management or streaming.

Potential Vulnerabilities
- If VNC is exposed and not properly secured, it could allow unauthorized remote access.
- Ensure strong authentication and encryption are enabled if VNC is required.
- This service might be used for remote management or streaming. If unnecessary, it should be disabled to reduce the attack surface.
- 
### Task #4
Perform an Nmap Scan Using Options
