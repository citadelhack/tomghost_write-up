# tomghost_write-up
## Recon
### nmap -A 
![nmap scan](https://github.com/citadelhack/tomghost_write-up/blob/main/tomghost/decryptattempt.png)

### HTTP
![webpage](https://github.com/citadelhack/tomghost_write-up/blob/main/tomghost/webhomepage.png)

### mfsconsole
![msfconsole exploit search](https://github.com/citadelhack/tomghost_write-up/blob/main/tomghost/foundexploit.png)

## Exploitation
### msf exploit
![setting up msf exploit](https://github.com/citadelhack/tomghost_write-up/blob/main/tomghost/exploitsetup.png)

![running exploit](https://github.com/citadelhack/tomghost_write-up/blob/main/tomghost/exploitoutput.png)

### accessing machine
![accessing the skyf**k user account](https://github.com/citadelhack/tomghost_write-up/blob/main/tomghost/skyfaccess.png)

### first flag
![finding first flag after messing around](https://github.com/citadelhack/tomghost_write-up/blob/main/tomghost/flag1.png)

### getting credentials
![funny looking files](https://github.com/citadelhack/tomghost_write-up/blob/main/tomghost/encryptedcrap.png)

![looky here](https://github.com/citadelhack/tomghost_write-up/blob/main/tomghost/pgpkey.png)

![decrypt attempt failed](https://github.com/citadelhack/tomghost_write-up/blob/main/tomghost/decryptattempt.png)

!["researched" and found out how to do this](https://github.com/citadelhack/tomghost_write-up/blob/main/tomghost/files2kali.png)

![password finding](https://github.com/citadelhack/tomghost_write-up/blob/main/tomghost/gpg2john.png)

![plain text](https://github.com/citadelhack/tomghost_write-up/blob/main/tomghost/merlinpass.png)

### privilege escalation and second flag
![merlin access](https://github.com/citadelhack/tomghost_write-up/blob/main/tomghost/merlinaccess.png)

![exploiting sudo zip](https://github.com/citadelhack/tomghost_write-up/blob/main/tomghost/zipgtfo.png)

![2nd flag](https://github.com/citadelhack/tomghost_write-up/blob/main/tomghost/flag2.png)

