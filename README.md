<h1>Hacking Metasploitable</h1>

<h2>Description</h2>
This project involves using Kali Linux to explore and exploit vulnerabilities in Metasploitable 2, a deliberately insecure Linux virtual machine designed for testing and training purposes. The objective is to understand common security flaws, how they are exploited, and how to mitigate them.
<br />

<h2>Skills Obtained</h2>

- <b>Network Scanning and Enumeration: </b> Using tools like Nmap to discover hosts, open ports, and services running on a network.
- <b>Vulnerability Identification:</b> Identifying common vulnerabilities in systems and applications.
- <b>Exploitation Techniques:</b> Using Metasploit and other tools to exploit identified vulnerabilities.
- <b>Password Cracking:</b> Use tools like Hydra to perform brute-force attacks and understand password security.
- <b>Web Application Testing:</b> Identifying and exploit vulnerabilities in web applications using tools like Burp Suite and Nikto.
- <b>Traffic Analysis:</b> Using Wireshark to capture and analyze network traffic, helping to understand how data flows in a network and how attacks can be detected.
- <b>Post-Exploitation:</b> Techniques for maintaining access and gathering further information after exploiting a system.
- <b>Mitigation Strategies</b> The methods to secure systems and prevent the exploitation of similar vulnerabilities in real-world scenarios.

<h2>Utilities Used</h2>

- <b>Nmap</b> 
- <b>Metasploit Framework</b>
- <b>Netcat</b> 
- <b>Burp Suite </b> 
- <b>Wireshark</b> 
- <b>Nikto</b>
- <b>Hydra</b>
 <h2>Environments Used </h2>

- <b>Target Environment: </b> Metasploitable VM
- <b>Attacker Environment:</b> Kali Linux VM  

<h2>Project walk-through:</h2>
<h3>User Enumeration through SMTP</h3>
<p align="center">
Step 1: Ensuring both VMs are on the same network <br/>
<img src="https://i.imgur.com/Sh3tT2J.png" height="80%" width="80% alt="Sploit"/>
<br />
<br />
Step 2: Scan the target server using NMAP  <br/>
<img src="https://i.imgur.com/5yfQhPY.png" height="80%" width="80%" alt="Sploit"/>
<br />
<br />
Step 3: Open Metasploit Framework, After Identifying which port we will exploit. <br/>
Step 4: Enter “grep scanner search smtp” as a command <br/>
<img src="https://i.imgur.com/2TW7pxr.png" height="80%" width="80%" alt="Sploit"/>
<br />
<br />
Set metasploitable (Target VM) as RHOSTS  <br/> 
<img src="https://i.imgur.com/GqdjqJl.png" height="80%" width="80%" alt="Pi-Hole steps"/>
<br />
<br />
As per below image, we're going to exploit unix_users.txt  <br/>
<img src="https://i.imgur.com/apeVO4V.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Step 5: Verifying if users are really found.  <br/>
 <br/>
 If we Verify "backup", the result will be positive but if we check another user which is snot included (ex: test), we’ll get a negative result.<br/>
 <br/>
 <h1 align="center">THANK YOU</h1>
</p>



<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>

