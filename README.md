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

![image](https://github.com/user-attachments/assets/de201df3-e6ba-43c0-8205-86527275727b)

The command sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:

![image](https://github.com/user-attachments/assets/cc752c52-8353-4db7-8372-a6e02a60d5ba)

![set1](https://github.com/user-attachments/assets/1886f95c-c372-441c-8c63-6badd1c2e827)




It displays the following menu and select 2 for Website Attack Vectors:

![set2](https://github.com/user-attachments/assets/10329492-b036-46f4-8ea8-f0c972e6bc5e)


The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected:

![image](https://github.com/user-attachments/assets/2828cdb0-7441-4915-8dcb-d8ea8dc79786)


The Credential Harvester Attack Method displays the following menu. In git push origin mthis menu1 for Web Templates is selected:
![image](https://github.com/user-attachments/assets/f88dda0e-cf24-4414-becf-ba9174f46487)



It shows the following screen in which the ip address of the attacker need to be given which is the default value:

It shows the following screen in which the option Google can be selected:
![image](https://github.com/user-attachments/assets/1ce5b0ec-7df1-440a-a137-07e9fe113cfa)

SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:

![image](https://github.com/user-attachments/assets/03e72210-551b-4d76-a496-7cce7d421834)



In windows IE, on giving the url http://192.168.169.88, the fake Google page is displayed. The victim can enter the username and password
![image](https://github.com/user-attachments/assets/604c2c33-feaf-4abb-a9bd-eb524681339f)


SET logs the information regarding the Google credentials:
![image](https://github.com/user-attachments/assets/08b1dc35-cc01-42ed-9135-d198d4d9af16)


SET logs the information in the xml file under /root/.set directory:
![image](https://github.com/user-attachments/assets/897f0b93-bc5f-4583-8be8-c4271e369ee6)


## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
