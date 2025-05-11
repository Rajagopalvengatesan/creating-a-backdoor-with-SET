# EX 7: CREATING A BACKDOOR WITH SOCIAL ENGINEERING TOOLKIT (SET)
creating a backdoor with SET - Ethical Hacking Techniques course

# AIM:
To Create a backdoor with Social Engineering Toolkit (SET)
```
Register Number: 212223240134
Name: RAJAGOPAL V
```
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
![WhatsApp Image 2025-04-21 at 01 01 18_c77e180a](https://github.com/user-attachments/assets/acdc511d-e764-4b0c-b32c-02fbf4c17768)


sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:

It displays the following menu and select 2 for Website Attack Vectors:
![WhatsApp Image 2025-04-21 at 01 01 44_148695c7](https://github.com/user-attachments/assets/6f4ba04b-21cb-425a-9b4c-114799c94f7d)



The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected:

![WhatsApp Image 2025-04-21 at 01 02 11_b77cfc06](https://github.com/user-attachments/assets/c223aeb6-232e-4342-b18c-3b628282e07e)




The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:

![WhatsApp Image 2025-04-21 at 01 03 05_23e32342](https://github.com/user-attachments/assets/ce3a4163-d7fa-48f6-aefa-e4ca6c001214)




It shows the following screen in which the ip address of the attacker need to be given which is the default value:

![WhatsApp Image 2025-04-21 at 01 03 47_49aee37f](https://github.com/user-attachments/assets/1f75da00-90f8-41b7-9df1-c2a912569e26)



It shows the following screen in which the option Google can be selected:

![WhatsApp Image 2025-04-21 at 01 04 09_c5ad131a](https://github.com/user-attachments/assets/3c32a29b-39f9-4558-841d-fcf79e612299)




SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:

![WhatsApp Image 2025-04-21 at 01 04 37_041dbaf0](https://github.com/user-attachments/assets/b608d2c8-d9f7-4b10-845a-0376eba58c19)




In windows IE, on giving the url http://192.168.1.4, the fake Google page is displayed. The victim can enter the username and password

![WhatsApp Image 2025-04-21 at 01 22 34_d759a76a](https://github.com/user-attachments/assets/c0ab7136-1ef1-4496-af6f-500878dd7ef3)



SET logs the information regarding the Google credentials:

![WhatsApp Image 2025-04-21 at 01 23 14_4e932089](https://github.com/user-attachments/assets/2760db48-1385-44bf-a2d1-96d830777fc5)



SET logs the information in the xml file under /root/.set directory:

![image](https://github.com/user-attachments/assets/eb860581-4b9f-4923-b762-13423fb56ee0)


## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
