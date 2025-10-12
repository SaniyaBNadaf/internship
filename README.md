Author: Saniya B Nadaf
Email: saniyanadaf300@gmail.com

Basic Linux:
pwd
ls -la
cd /path/to
mkdir folder
touch file.txt
chmod 600 file.txt

Network Commands:
ip a
ifconfig
ping <target-ip>
traceroute 8.8.8.8
netstat -tulpen

Nmap Scan:
nmap -sS -sV -O <target-ip> -oN reports/nmap_target.txt

Wireshark:
Filter: icmp or http
Capture on host-only interface

Netcat:
Listener: nc -lvp 4444
Client: nc <target-ip> 4444

OpenSSL:
echo -n "hello" | sha256sum
openssl genpkey -algorithm RSA -out key.pem -pkeyopt rsa_keygen_bits:2048

📄 3. setup_instructions.md
touch setup_instructions.md
