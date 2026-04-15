# 🔍 Nmap TryHackMe Write-Up

---

## 🧩 Task 2

**What networking constructs are used to direct traffic to the right application on a server?**  
Ports  

**How many of these are available on any network-enabled computer?**  
65535  

**How many of these are considered "well-known"?**  
1024  

---

## ⚙️ Task 3

**What is the first switch listed in the help menu for a 'Syn Scan'?**  
-sS  

**Which switch would you use for a "UDP scan"?**  
-sU  

**If you wanted to detect which operating system the target is running on, which switch would you use?**  
-O  

**Nmap provides a switch to detect the version of the services running on the target. What is this switch?**  
-sV  

**How would you increase the verbosity?**  
-v  

**How would you set the verbosity level to two?**  
-vv  

**What switch would you use to save the nmap results in three major formats?**  
-oA  

**What switch would you use to save the nmap results in a "normal" format?**  
-oN  

**How would you save results in a "grepable" format?**  
-oG  

**How would you activate aggressive mode?**  
-A  

**How would you set the timing template to level 5?**  
-T5  

**How would you tell nmap to only scan port 80?**  
-p 80  

**How would you tell nmap to scan ports 1000-1500?**  
-p 1000-1500  

**How would you tell nmap to scan all ports?**  
-p-  

**How would you activate a script from the nmap scripting library?**  
--script  

**How would you activate all of the scripts in the "vuln" category?**  
--script=vuln  

---

## 🌐 Task 5

**Which RFC defines the appropriate behaviour for the TCP protocol?**  
RFC 9293  

**If a port is closed, which flag should the server send back to indicate this?**  
RST  

---

## 🔍 Task 6

**There are two other names for a SYN scan, what are they?**  
Half-Open, Stealth  

**Can Nmap use a SYN scan without Sudo permissions (Y/N)?**  
N  

---

## 📡 Task 7

**If a UDP port doesn't respond to an Nmap scan, what will it be marked as?**  
open|filtered  

**When a UDP port is closed, which protocol is used to send "port unreachable"?**  
ICMP  

---

## 🎄 Task 8

**Which of the three shown scan types uses the URG flag?**  
xmas  

**Why are NULL, FIN and Xmas scans generally used?**  
Firewall Evasion  

**Which common OS may respond with a RST for every port?**  
Microsoft Windows  

---

## 🌍 Task 9

**How would you perform a ping sweep on the network?**  
nmap -sn 172.16.0.0/16  

---

## 🧠 Task 10

**What language are NSE scripts written in?**  
Lua  

**Which category of scripts is dangerous in production?**  
intrusive  

---

## 📁 Task 11

**What optional argument can ftp-anon.nse take?**  
maxlist  

---

## 🖥️ Task 12

**What is the filename of the SMB OS detection script?**  
smb-os-discovery.nse  

**What does this script depend on?**  
smb-brute  

---

## 🚫 Task 13

**Which protocol is often blocked requiring -Pn?**  
ICMP  

**Which switch appends random data to packets?**  
--data-length  

---

## 🎯 Task 14

**Does the target respond to ICMP (Y/N)?**  
N  

**Perform an Xmas scan (1–999). How many ports are open|filtered?**  
999  

**Reason?**  
No Response  

**Perform a SYN scan (1–5000). How many ports are open?**  
5  

**Can Nmap login to FTP using ftp-anon (Y/N)?**  
Y  
