[Coursera OX90B7LLU6XM.pdf](https://github.com/user-attachments/files/18872020/Coursera.OX90B7LLU6XM.pdf)
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
![image](https://github.com/user-attachments/assets/ced82610-8f5f-4e03-871f-de795500da3c)
![image](https://github.com/user-attachments/assets/1d563062-c6e6-41e1-a7b4-1394b1f27f45)
the system to attacks such as brute force or the exploitation of open SSH
nmap -A -T4 scanme.nmap.org
### Key Takeaways
- Options can help you get more accurate results, faster scans, and customized output
- Options enable you to further assess the network
### Task #5
Output Nmap Scan Results to a File
nmap p 80A-ON scan.txt scanme.nmap.org/30
![image](https://github.com/user-attachments/assets/c8c15ef9-b8dc-4c75-97eb-490dedf9b099)
Port 80 open
Scan.txt
![image](https://github.com/user-attachments/assets/f083a360-f2c5-4278-a675-874fe7767edd)
cat scan.txt to check the file
![image](https://github.com/user-attachments/assets/12e33bbe-3251-4042-8728-c5b5bf587e12)
### Key Takeaways
- The man page fornmap has various sections with options that you often for scanning will reference
- Make sure you are authorized to perform scans on targets
- Adding certain options can make your scan more aggressive and will typically take longer to complete.
### Cumulative Challenge
1) Perform a nmap scan, scanning ports 22-80, on target: scanme.nmap.org
2) Use the appropriate option to enable OS and version detection, script scanning, and traceroute
3) Set your scan to -T3 for the timing execution of the scan
nmap -p22-80 -A -T3 scanme.nmap.org -oN output.txt
![image](https://github.com/user-attachments/assets/b0ea9bc5-ef71-4ee1-bf5a-bf0aa4c29881)
4) Output the scan results to a txt file named: output.txt
5) Verify the contents of the output.txt file
cat output.txt
![image](https://github.com/user-attachments/assets/d6020061-7f8e-4136-9fa8-5597d49c957b)
6) Be sure to reference your nmap man page for help
no need to
***
A basic Nmap cheat sheet
[nmap cheat sheet v1_guided project.pdf](https://github.com/user-attachments/files/18871874/nmap.cheat.sheet.v1_guided.project.pdf)

For more information on Nmap visit 
nmap.org
  
