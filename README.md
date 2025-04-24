# ARP-Attack-and-Network-Sniffing
# Explore Network Sniffing and ARP Attacks

## Developed By : SANJAY M
## Register No  : 212223230187

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

![{EF3F15FD-71B8-4CAD-89AB-1EE910702541}](https://github.com/user-attachments/assets/34fd95fe-3fc3-4d5b-9b3a-e31c9551af5f)


From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:


![{813EAD40-9C16-46E5-AA31-16AAF53F63ED}](https://github.com/user-attachments/assets/96ceffe8-51d7-440b-ba73-07fb9b451140)



 dsniff:


In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org


## OUTPUT:


![image](https://github.com/user-attachments/assets/cae623b8-5cea-46ea-8ce2-4ca2966806d1)




In Kali issue the following commands:
sudo dsnifff
## OUTPUT:





Invoke the wireshark and examine the various menus  and controls of the tool:

![{EF73C77A-180D-4378-897F-49EB8C6DB653}](https://github.com/user-attachments/assets/cc675d18-debe-42a3-8b3c-58fecac61d5f)

## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully

