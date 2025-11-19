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

<img width="1114" height="757" alt="Screenshot 2025-11-13 082434" src="https://github.com/user-attachments/assets/56ac0c58-ec53-472d-9c6e-bf503fc546ff" />


The command sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:
## OUTPUT

<img width="669" height="462" alt="image" src="https://github.com/user-attachments/assets/b2ffeb5c-7471-4782-8e03-c65012e3f5bf" />


It displays the following menu and select 2 for Website Attack Vectors:
## OUTPUT

<img width="662" height="296" alt="Screenshot 2025-11-13 082649" src="https://github.com/user-attachments/assets/64c30057-3682-40ac-871c-4116baae70be" />


The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:
## OUTPUT

<img width="1099" height="205" alt="Screenshot 2025-11-13 082926" src="https://github.com/user-attachments/assets/1a54b4e0-17f8-489d-ae41-2b5beddd7655" />


It shows the following screen in which the ip address of the attacker need to be given which is the default value:
## OUTPUT


<img width="870" height="400" alt="Screenshot 2025-11-13 083013" src="https://github.com/user-attachments/assets/25b7ce0c-8aa6-4e22-a8a0-93f95952eedb" />


It shows the following screen in which the option Google can be selected:
## OUTPUT



<img width="870" height="400" alt="Screenshot 2025-11-13 083013" src="https://github.com/user-attachments/assets/cbb07301-3f65-4965-81c9-7e39552e73b3" />


SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:
## OUTPUT

<img width="1129" height="143" alt="image" src="https://github.com/user-attachments/assets/3280520e-977a-4306-a509-43713354b6f2" />



In windows IE, on giving the url http://192.168.1.2 (use appropriate IP address), the fake Google page is displayed. The victim can enter the username and password
## OUTPUT
<img width="1408" height="736" alt="ss" src="https://github.com/user-attachments/assets/89011378-610d-4bd0-afe8-dad2b500f8ca" />

SET logs the information regarding the Google credentials:
## OUTPUT
<img width="1230" height="370" alt="Screenshot 2025-11-13 083632" src="https://github.com/user-attachments/assets/fe9afca6-bd18-4ace-8463-0d04a3d152dd" />



SET logs the information in the xml file under /root/.set directory:




## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
