# creating-a-backdoor-with-SET
creating a backdoor with SET - Ethical Hacking Techniques course

# AIM:
To Create a backdoor with Social Engineering Toolkit (SET)

## DESIGN STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode


### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:

Open terminal and try execute some kali linux commands

## EXECUTION STEPS AND ITS OUTPUT:
Social Engineering attacks are the various cons used by the hackers to trick people into providing sensitive data to the attackers. 
The command sudo setoolkit in the prompt gives menu with set prompt:

![image](https://github.com/user-attachments/assets/b3baad1a-11de-49e8-99c0-1bb9ff3a7940)

 It displays the following menu and select 2 for Website Attack Vectors:
 ![image](https://github.com/user-attachments/assets/ac9c5592-bf19-4a93-868f-aefa85ba8d69)
 
 The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected:
![image](https://github.com/user-attachments/assets/a31420c0-6e16-446d-b6da-7ad7789034f2)

The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:
![image](https://github.com/user-attachments/assets/cc20b877-12c8-42a3-a802-d919043336e7)

It shows the following screen in which the ip address of the attacker need to be given which is the default value: 
![image](https://github.com/user-attachments/assets/f6314e0b-3256-49a7-98a1-f1a9d39820bf)

It shows the following screen in which the option Google can be selected:
![image](https://github.com/user-attachments/assets/5a2d64a8-56e4-4f58-88fe-8f9e5a568b81)

SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:
![image](https://github.com/user-attachments/assets/238e9e69-5ee4-437f-a9c0-1d5dc07470de)

In windows IE, on giving the url http://192.168.1.2, the fake Google page is displayed. The victim can enter the username and password
![image](https://github.com/user-attachments/assets/e632908b-bfdd-4391-8b94-518dca7047f9)

SET logs the information regarding the Google credentials:
![image](https://github.com/user-attachments/assets/2b8a0ded-5a36-4fe5-8ee2-47ebcdbef4de)

SET logs the information in the xml file under /root/.set directory:
![image](https://github.com/user-attachments/assets/bbdf3e3e-74ae-44f3-b868-9b5b9a85ebb7)

## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
