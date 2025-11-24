# ARP-Attack-and-Network-Sniffing
# Explore Network Sniffing and ARP Attacks

# AIM:

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
<img width="772" height="433" alt="111" src="https://github.com/user-attachments/assets/98fbac53-02a8-4ee8-af80-9ba7783d44cc" />


From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:

<img width="786" height="518" alt="222" src="https://github.com/user-attachments/assets/3e197a12-6ea0-45b6-9cb0-f1bbbd50c4f3" />

 dsniff:


<img width="805" height="137" alt="333" src="https://github.com/user-attachments/assets/919a7f18-4046-4674-8eef-1c58f09ee932" />




In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:

<img width="1475" height="613" alt="444" src="https://github.com/user-attachments/assets/70b4132d-041c-43af-a012-728d70269e49" />



In Kali issue the following commands:
sudo dsnifff
## OUTPUT:

<img width="1483" height="732" alt="555" src="https://github.com/user-attachments/assets/3c82b53e-27f4-4a91-93b1-535cb4eb62c0" />


Invoke the wireshark and examine the various menus  and controls of the tool:


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
