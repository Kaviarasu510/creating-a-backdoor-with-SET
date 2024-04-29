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

![7 1](https://github.com/Kaviarasu510/creating-a-backdoor-with-SET/assets/119392695/60d2439c-6804-4407-926b-112579f53b07)

The command sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:

![7 2](https://github.com/Kaviarasu510/creating-a-backdoor-with-SET/assets/119392695/70b2568c-7b49-4e4c-b585-486c401a2a28)

It displays the following menu and select 2 for Website Attack Vectors:

![7 3](https://github.com/Kaviarasu510/creating-a-backdoor-with-SET/assets/119392695/332ce4a1-fed5-466d-a5b3-9eb296bfa317)

The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected:

![7 4](https://github.com/Kaviarasu510/creating-a-backdoor-with-SET/assets/119392695/4a0df1ad-a36e-41c8-a9a4-ce6f7a4d3e8e)

The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:

![7 5](https://github.com/Kaviarasu510/creating-a-backdoor-with-SET/assets/119392695/8928d0c2-d406-4d90-b945-68d9ae3bfce2)

It shows the following screen in which the ip address of the attacker need to be given which is the default value:

![7 6](https://github.com/Kaviarasu510/creating-a-backdoor-with-SET/assets/119392695/c7cd2efa-3837-46ed-824a-9acd4b1916cc)

It shows the following screen in which the option Google can be selected:

![7 7](https://github.com/Kaviarasu510/creating-a-backdoor-with-SET/assets/119392695/aa28e001-c0e1-42a5-a641-2987b925d08b)

SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:

![7 8](https://github.com/Kaviarasu510/creating-a-backdoor-with-SET/assets/119392695/b6770741-0ac3-40b9-9b0e-9559b6c35547)

In windows IE, on giving the url http://192.168.1.2, the fake Google page is displayed. The victim can enter the username and password

![image](https://github.com/Kaviarasu510/creating-a-backdoor-with-SET/assets/119392695/929238e0-f089-4f45-8fa2-37132f0b01c3)

SET logs the information regarding the Google credentials:

![image](https://github.com/Kaviarasu510/creating-a-backdoor-with-SET/assets/119392695/ba9d0e16-3df0-4543-8b04-b402c1c9db6f)

SET logs the information in the xml file under /root/.set directory:

![image](https://github.com/Kaviarasu510/creating-a-backdoor-with-SET/assets/119392695/9c391b3a-5ee9-4528-aea4-066dbf855d7d)

## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
