# 4.Execution_of_NetworkCommands
## NAME: JOANN ELIZABETH 
## REGISTER NUMBER : 212224040139

## AIM
Use of Network commands in Real Time environment

## Software :
Command Prompt And Network Protocol Analyzer

## Procedure:
To do this EXPERIMENT- follows these steps:
In this EXPERIMENT- students have to understand basic networking commands e.g cpdump, netstat, ifconfig, nslookup ,traceroute and also Capture ping and traceroute PDUs using a network protocol analyzer
All commands related to Network configuration which includes how to switch to privilege mode
and normal mode and how to configure router interface and how to save this configuration to
flash memory or permanent memory.
This commands includes
• Configuring the Router commands
• General Commands to configure network
• Privileged Mode commands of a router
• Router Processes & Statistics
• IP Commands
• Other IP Commands e.g. show ip route etc.

## PROGRAM:
```
## CLIENT:
import socket from pythonping import ping s=socket . socket ( )
s . ' localhost ' 8000))
s . listen(5)
while True:
hostname=c . recv(1024) . decode( ) try :
c . send(str(ping(hostname, verbose=Fa1se)) . encode()) except KeyError:
c . send("Not Found" . encode())

## SERVER:
import socket s=socket . socket()
s .  localhost' , 8000)) while True:
ip=input("Enter the website you want to ping 
s . send(ip.encode()) print(s . recv(1Ø24) . decode())

## TRACEROUTE COMMAND:
from scapy.all import*
target [ "www.google . com" ]
result, unans - traceroute(target,maxtt1=32)
 print (result, unans)
```
## OUPUT
## PING :
![image](https://github.com/user-attachments/assets/764682b2-141f-4f92-8516-36f716bb4d8c)

## TRACERT:
![image](https://github.com/user-attachments/assets/f5bd5149-d0e9-4c3d-8254-241825e554a5)

## IPCONFIG :
![image](https://github.com/user-attachments/assets/9622baa4-c38a-427d-aa9c-5951b7cf97bd)

## NETSTAT:
![image](https://github.com/user-attachments/assets/637b686b-5199-4ee4-904c-c31f72e00caa)

## FTP HOST:
![image](https://github.com/user-attachments/assets/4f098fc3-ca28-4d1c-8e28-975c7337743a)

## RESULT
Thus, python program to perform stop and wait protocol was successfully executed
