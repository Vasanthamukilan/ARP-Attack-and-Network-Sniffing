# ARP-Attack-and-Network-Sniffing

# Explore Network Sniffing and ARP Attacks

## AIM:

To explore network sniffing and ARP Attacks

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:


### Step 3:
Open terminal and try execute some kali linux commands

## ARP Attacks:  
ARP spoofing: A hacker sends fake ARP packets that link an attacker's MAC address with an IP of a computer already on the LAN. 
Boot kali and Windows7 virtual machines.
In windows 7 give the command arp -a
## OUTPUT:
![268916636-93e3d23d-50e3-4400-9aab-51a656d60f4c](https://github.com/Vasanthamukilan/ARP-Attack-and-Network-Sniffing/assets/119559694/e08ef703-2e48-4a83-95b8-a64eeffb19de)

From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:
![268916710-4d20702c-34d4-46cf-b093-6c82a51300ba](https://github.com/Vasanthamukilan/ARP-Attack-and-Network-Sniffing/assets/119559694/94aec180-c662-44cb-805a-9b0f0a1593c7)


 dsniff:

In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:
![268916772-6ae8c93d-4b79-40ef-9b4a-596a47f25aaa](https://github.com/Vasanthamukilan/ARP-Attack-and-Network-Sniffing/assets/119559694/8fbe6cb3-b1d1-42ff-a94f-e06c3300b7d3)

In Kali issue the following commands:
sudo dsnifff
## OUTPUT:
![268916912-258e7cb1-b78a-4cbc-a27d-1aaf04ce470a](https://github.com/Vasanthamukilan/ARP-Attack-and-Network-Sniffing/assets/119559694/6cdf0fd8-9c96-4372-a556-b3c5ddf6d12d)

Invoke the wireshark and examine the various menus  and controls of the tool:
![268916953-9b1c8c1b-4f36-4b02-8641-7e8ffd9affa1](https://github.com/Vasanthamukilan/ARP-Attack-and-Network-Sniffing/assets/119559694/52786916-895b-4026-b06c-6eb55ba9408b)



## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
