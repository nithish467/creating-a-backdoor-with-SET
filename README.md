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
## OUTPUT
<img width="939" height="891" alt="image" src="https://github.com/user-attachments/assets/803f02d1-f459-44b4-a18c-e2e34d023644" />



The command sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:
## OUTPUT

<img width="420" height="245" alt="image" src="https://github.com/user-attachments/assets/8f28eb6c-382e-4b9e-9e94-8d9383ebe2cb" />


It displays the following menu and select 2 for Website Attack Vectors:
## OUTPUT

<img width="494" height="325" alt="image" src="https://github.com/user-attachments/assets/4be50fdf-33bb-4f52-9ec7-626075ce2a36" />


The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:
## OUTPUT
<img width="420" height="228" alt="image" src="https://github.com/user-attachments/assets/ffdd2765-ab69-47ec-86ce-80e7a5f1656b" />

The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:

## OUTPUT 

<img width="344" height="149" alt="image" src="https://github.com/user-attachments/assets/1464285b-aaa8-422d-b80b-c52e9418f665" />


It shows the following screen in which the ip address of the attacker need to be given which is the default value:
## OUTPUT

<img width="764" height="537" alt="image" src="https://github.com/user-attachments/assets/b2e0292c-6119-4080-be74-2c65f30cafc8" />



It shows the following screen in which the option Google can be selected:
## OUTPUT

<img width="805" height="457" alt="image" src="https://github.com/user-attachments/assets/9f4e4587-ec94-43da-a4bc-1bfe76618c1d" />




SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:
## OUTPUT

<img width="938" height="213" alt="image" src="https://github.com/user-attachments/assets/08af1c55-b9fa-46d6-b948-7cc2d66633a2" />



In windows IE, on giving the url http://192.168.1.2 (use appropriate IP address), the fake Google page is displayed. The victim can enter the username and password
## OUTPUT
<img width="956" height="930" alt="image" src="https://github.com/user-attachments/assets/8ebb7f55-bb14-4904-a636-564b686fe288" />


SET logs the information regarding the Google credentials:
## OUTPUT

<img width="946" height="534" alt="image" src="https://github.com/user-attachments/assets/a0a807dc-e530-463a-a1ef-722ff8d0073d" />


SET logs the information in the xml file under /root/.set directory:
## OUTPUT

<img width="1332" height="479" alt="image" src="https://github.com/user-attachments/assets/d4c613cf-2702-41c0-8321-c63599628dae" />










## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
