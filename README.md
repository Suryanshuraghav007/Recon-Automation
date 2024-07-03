# Recon-Automation
# Bug-Bounty-Automation
Bash Script to perform bug bounty automation

<b>Requirements</b> -
•	Kali Linux, Virtual box
•	Python and Golang
•	Sublister, Eyewitness
•	Assetfinder, Amass, Httprobe
•	Nmap, Sqlmap

<b>Scope</b> - It provides insight into how ethical hackers identify vulnerabilities in web applications, mobile apps, and other platforms using a range of tools and scripts

<b>Implementation</b> - In this project, automation of tools or scripts is essential to consolidate all tasks into a single execution on the target website. Two approaches are available: using bash scripting or Python. Opting for bash scripting, we must install Golang to facilitate automating multiple script commands within a single shell script. Initial steps involve gathering requirements and selecting tools that efficiently perform reconnaissance on the target website, producing comprehensible outputs. The bash script will iterate through multiple scripts, executing each recon tool sequentially, with the output of each tool stored in a designated text file.

<b> vi install.sh
  chmod +x install.sh
  ./install.sh
</b>
<br>
<b> vi recon.sh
  chmod +x recon.sh
  ./recon.sh <website.com>
</b>
  
