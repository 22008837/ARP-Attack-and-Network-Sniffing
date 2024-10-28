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
![Screenshot 2023-09-26 205133](https://github.com/Reebak04/ARP-Attack-and-Network-Sniffing/assets/118364993/af970103-9fb9-429d-acf8-1f5d094219ca)

From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:
![image](https://github.com/user-attachments/assets/dbd6fde3-af2f-4475-839e-67db8bedb96c)

dsniff:In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org
## OUTPUT:
![image](https://github.com/user-attachments/assets/7281486f-2d1c-4b09-b702-4c32000017b5)

In Kali issue the following commands:
sudo dsnifff
## OUTPUT:
![image](https://github.com/user-attachments/assets/3f565d9f-68ab-42f1-a5c8-42fe04acefdd) 

## wireshark :
Invoke the wireshark and examine the various menus  and controls of the tool:
![ws](https://github.com/Reebak04/ARP-Attack-and-Network-Sniffing/assets/118364993/53d046a7-f3d4-44db-b00c-4757086bb690)
## ettercap :
ettercap supports active and passive dissection of many protocols and includes many features for network and host analysis.
![ettercap](https://github.com/Reebak04/ARP-Attack-and-Network-Sniffing/assets/118364993/88e2faef-2c64-410b-bcce-0072e4d0f85f)

## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
