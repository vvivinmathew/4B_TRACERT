# 4B_SIMULATING_TRACEROUTE_COMMAND 
## EXP: 4(b) 
## DATE: 24/04/2025
 
## AIM: 
To write the python program for simulating Traceroute command 
 
## ALGORITHM: 
1. Start the program. 
2. Get the frame size from the user. 
3. To create the frame based on the user request. 
4. To send frames to server from the client side. 
5. If your frames reach the server, it will send ACK signal to client 
otherwise it will send NACK signal to client. 
6. Stop the program 
 
## PROGRAM: 
 
from scapy.all import* 
target = ["www.google.com"] 
result, unans = traceroute(target,maxttl=32) 
print(result,unans) 
 
## OUTPUT: 

 ![Screenshot 2025-04-17 140605](https://github.com/user-attachments/assets/e160e97a-bccc-4bf2-bcdb-657de801bd3b)

 
## RESULT: 
 
Thus, the python program for simulating Traceroute command was successfully executed.
