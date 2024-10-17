# CN-Lab-7-12
Lab 7: Implementation of RIP Version 1

●	Procedure:
1.	Open Packet Tracer:
■	Launch Cisco Packet Tracer on your computer.
2.	Create a Network:
■	Drag three routers onto the workspace and connect them in a linear topology.
■	Connect a computer to each router using Ethernet cables.
3.	Configure IP Addresses:
■	Assign IP addresses to each interface on the routers and computers.
4.	Enable RIP Version 1:
■	Access the CLI of each router.
■	Enable RIP routing: router rip, version 1.
■	Advertise connected networks: network <network address>.
5.	Test Connectivity:
■	Use the ping command to test connectivity between the computers.


Output:
![image](https://github.com/user-attachments/assets/a328525b-38e9-4810-838c-18f97c8c177e)
![image](https://github.com/user-attachments/assets/3d23f3a7-3389-434e-80a1-9c27ee759790)
![image](https://github.com/user-attachments/assets/76b4e120-5391-4855-9258-35f88bfc5f5b)
 
Lab 8: Implementation of RIP Version 2

●	Procedure:
1.	Open Packet Tracer:
■	Launch Cisco Packet Tracer on your computer.
2.	Create a Network:
■	Drag three routers onto the workspace and connect them in a linear topology.
■	Connect a computer to each router using Ethernet cables.
3.	Configure IP Addresses:
■	Assign IP addresses to each interface on the routers and computers.
4.	Enable RIP Version 2:
■	Access the CLI of each router.
■	Enable RIP routing: router rip, version 2.
■	Advertise connected networks: network <network address>.
5.	Test Connectivity:
■	Use the ping command to test connectivity between the computers.


Output:

![image](https://github.com/user-attachments/assets/f18bdf82-07ed-4ffa-9928-80ce9e2d8b7a)

 ![image](https://github.com/user-attachments/assets/de4bff13-ba14-41a6-9908-788811756b73)

 ![image](https://github.com/user-attachments/assets/7311d51b-d4e9-448c-8212-d86373d62e3d)
 
Lab 9: Implementation of Single Area OSPF

●	Procedure:
1.	Open Packet Tracer:
■	Launch Cisco Packet Tracer on your computer.
2.	Create a Network:
■	Drag three routers onto the workspace and connect them in a triangular topology.
■	Connect a computer to each router using Ethernet cables.
3.	Configure IP Addresses:
■	Assign IP addresses to each interface on the routers and computers.
4.	Enable OSPF:
■	Access the CLI of each router.
■	Enable OSPF: router ospf 1.
■	Advertise connected networks: network <network address> area 0.
5.	Test Connectivity:
■	Use the ping command to test connectivity between the computers.
Output:


![image](https://github.com/user-attachments/assets/75fcefd3-7a24-49aa-a844-1656ecc3468c)

 
 ![image](https://github.com/user-attachments/assets/cd081959-72de-4a72-b734-14c2db820779)



![image](https://github.com/user-attachments/assets/5ef46504-6ee4-4e49-ba9a-d8c2f4112134)


![image](https://github.com/user-attachments/assets/4d02fec4-8014-43df-acfa-93191d515949)

 
 ![image](https://github.com/user-attachments/assets/f669d402-4d9c-4e33-ab9b-faa8d3a7c657)

 
Lab 10: Implementation of Multi Area OSPF

●	Procedure:
1.	Open Packet Tracer:
■	Launch Cisco Packet Tracer on your computer.
2.	Create a Network:
■	Drag four routers onto the workspace and connect them to form two separate OSPF areas with an Area 0 backbone.
■	Connect a computer to each router using Ethernet cables.
3.	Configure IP Addresses:
■	Assign IP addresses to each interface on the routers and computers.
4.	Enable OSPF:
■	Access the CLI of each router.
■	Enable OSPF on Area 0 routers: router ospf 1.
■	Advertise connected networks: network <network address> area 0.
■	Enable OSPF on Area 1 routers: router ospf 1.
■	Advertise connected networks: network <network address> area
5.	Test Connectivity:
■	Use the ping command to test connectivity between the computers.


Output:


 ![image](https://github.com/user-attachments/assets/886349a1-a16a-4d70-a8bb-dabebccd3567)

 

![image](https://github.com/user-attachments/assets/3366efb5-b1d5-44ca-a483-5d62f25b6acb)


![image](https://github.com/user-attachments/assets/156b6c42-334b-4771-b2e8-f786ae3e4c7b)



![image](https://github.com/user-attachments/assets/d871fad3-65cf-4721-92fb-fa87589f62da)

 
 ![image](https://github.com/user-attachments/assets/13901938-02df-4ac0-9679-0e56313f6233)


![image](https://github.com/user-attachments/assets/90c84b84-cec7-42b7-a0c5-29735e27b9eb)



![image](https://github.com/user-attachments/assets/b32e313f-0f43-43fb-ab91-2bbd9d01865f)


Lab 11: PPP Configuration

●	Procedure:
1.	Open Packet Tracer:
■	Launch Cisco Packet Tracer on your computer.
2.	Create a Network:
■	Drag two routers onto the workspace and connect them using a serial connection.
■	Connect a computer to each router using Ethernet cables.
3.	Configure IP Addresses:
■	Assign IP addresses to each interface on the routers and computers.
4.	Configure PPP:
■	Access the CLI of each router.
■	Enter interface configuration mode for the serial interface: interface serial 0/0/0.
■	Enable PPP encapsulation: encapsulation ppp.
5.	Test Connectivity:
■	Use the ping command to test connectivity between the computers.
Output:
 ![image](https://github.com/user-attachments/assets/20d9f00a-6d6e-4000-a8f3-106332d4a930)

 

![image](https://github.com/user-attachments/assets/66d357ea-99c8-4250-971b-c9891982bd2f)





![image](https://github.com/user-attachments/assets/cf74eb87-f1b0-4c37-8037-2d2b9e18fc5e)



 

 ![image](https://github.com/user-attachments/assets/740aab6e-edc1-42f7-b1ba-333e0066e4fe)



![image](https://github.com/user-attachments/assets/542c7462-6bd9-4793-b9a6-09e9daf47fe7)

 
Lab 12: HDLC Configuration

●	Procedure:
1.	Open Packet Tracer:
■	Launch Cisco Packet Tracer on your computer.
2.	Create a Network:
■	Drag two routers onto the workspace and connect them using a serial connection.
■	Connect a computer to each router using Ethernet cables.
3.	Configure IP Addresses:
■	Assign IP addresses to each interface on the routers and computers.
4.	Configure HDLC:
■	Access the CLI of each router.
■	Enter interface configuration mode for the serial interface: interface serial 0/0/0.
■	Enable HDLC encapsulation: encapsulation hdlc.
5.	Test Connectivity:
■	Use the ping command to test connectivity between the computers.


Output:


![image](https://github.com/user-attachments/assets/217d881c-eff0-4dbe-b381-cfbd6b95f458)

![image](https://github.com/user-attachments/assets/51508e31-4816-4c9a-85e5-93fca119aa0c)

![image](https://github.com/user-attachments/assets/4115f181-882f-4c2a-b02a-05a4a377ca2a)











