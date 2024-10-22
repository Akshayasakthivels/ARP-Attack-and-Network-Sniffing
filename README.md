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

![WhatsApp Image 2024-10-22 at 21 43 58_1826c705](https://github.com/user-attachments/assets/1418c4da-3272-4c29-89bd-02f8cf77fb9a)


From kali linux issue the command :
sudo arpspoof -i eth0 -t <target system> <gateway>
## OUTPUT:

![WhatsApp Image 2024-10-22 at 21 52 03_955bc428](https://github.com/user-attachments/assets/ff3a67cc-7f80-40fa-826e-3694a68b0db0)

 dsniff:
 
In Metasploit open the ftp console as below. Also you can try other ftp websites ftp.vim.org

## OUTPUT:

![WhatsApp Image 2024-10-22 at 22 02 31_c6d99c58](https://github.com/user-attachments/assets/6447ad75-6ec8-4506-b1be-d93053f069d6)

In Kali issue the following commands:
sudo dsnifff

## OUTPUT:



Invoke the wireshark and examine the various menus  and controls of the tool:


## Ettercap
Ettercap supports active and passive dissection of many protocols (even encrypted ones) and includes many feature for network and host analysis. Ettercap can be used as sniffing tool as illustrated below:

![WhatsApp Image 2024-10-22 at 21 55 24_7d69b787](https://github.com/user-attachments/assets/2b75d0f6-ca16-4880-8176-2eb1e8860b9a)

![WhatsApp Image 2024-10-22 at 21 55 48_7746aad9](https://github.com/user-attachments/assets/dbd01e64-2073-471a-a9bd-cff12f4b1f24)


## RESULT:
The kali linux tools for ARP Attack and Network Sniffing were identified successfully
