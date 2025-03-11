# Creating VLANs Sophos XGS Firewall

*Ref 1: Network Diagram*

![image](https://github.com/user-attachments/assets/174e317d-c834-4846-aa3c-ecf411026e8c)

 

# Creates a VLAN with the ID and names to it
![image](https://github.com/user-attachments/assets/bd2a216d-c635-44ad-bf12-3696f2313c47)
 
# Verifying the configuration
![image](https://github.com/user-attachments/assets/f103b2ae-b1f3-48ec-bba1-5c202eeb640c)
 
# Adding the interfaces in VLANs and setting them as access
![image](https://github.com/user-attachments/assets/256f62ae-704a-4d8c-90f5-9b092f820e67)
 
# Verify the VLANs are in the database on each switch.
![image](https://github.com/user-attachments/assets/b9871888-69d6-4694-be7f-f710f437f602)

 
# Configuring the Gi0/0 interface as Trunk and tagging VLAN 10, 20 and 30 to it.
![image](https://github.com/user-attachments/assets/4be5331d-ebf8-4ac1-b870-612a747a7013)
 
# Viewing and verifying the default switchport status configuration
![image](https://github.com/user-attachments/assets/a4fdc096-01fc-4f0b-a23a-aceb02191998)
![image](https://github.com/user-attachments/assets/d0798860-93e5-4c28-98b5-b164de35a3b2)
 
 
The trunk mode is set to trunk and the interface operational mode is currently in the trunk mode using the default Trunking Native VLAN 1.
NB: Configure the trunk link to use VLAN 199 as the native VLAN for better security.
![image](https://github.com/user-attachments/assets/7e3b541b-07e2-47f0-aef1-8a893380209a)
 

# Verify the VLANs are in the database on each switch.
![image](https://github.com/user-attachments/assets/2cabfe68-29ba-4df7-b954-ea32b3380cb3)


# Assigning IP Addresses to VLANs
![image](https://github.com/user-attachments/assets/20aeaeaf-c61f-467a-a436-2ec68e81a2f2)

 
# Verifying the configuration
![image](https://github.com/user-attachments/assets/ed41225f-c4d6-4099-87e2-eebb3eaad0ff)
 
# Enabling L3 Inter-VLAN Routing on the Switch
![image](https://github.com/user-attachments/assets/949dbe15-d5bc-4abb-84ae-c7472bcf6dc0)
 
# Enabling DHCP Server for VLANs
![image](https://github.com/user-attachments/assets/7d42c460-ab87-4092-8951-484871060c80)
 
# Excluding IP Address from DHCP Server
 ![image](https://github.com/user-attachments/assets/2440b9a1-0a0c-459e-8853-a311cc927bb2)


# Verifying IP Address from DHCP Server are assigned to clients IT and Finance.
![image](https://github.com/user-attachments/assets/b9a044ec-7ec9-483e-9838-5673b905d72f)
![image](https://github.com/user-attachments/assets/cf557e1a-0f0a-43e2-903f-b76e039931ab)

 
 


# Verify the IT – VLAN 10 has connectivity to Finance – VLAN 20.
![image](https://github.com/user-attachments/assets/9918a103-4362-444d-86aa-13ab74d2c970)



 

# Add the IT – VLAN 10 and  Finance – VLAN 20 zones in the Firewall
![image](https://github.com/user-attachments/assets/de4ecc32-9ef2-47d6-91c4-0b52a95a8ee6)
 ![image](https://github.com/user-attachments/assets/d9bb262d-200b-42e7-ab14-3ad20dabae5d)
![image](https://github.com/user-attachments/assets/756793ef-ca87-433c-a138-25a5aff6f05f)
![image](https://github.com/user-attachments/assets/d09f78c8-5da8-4857-86dd-c0b40c87d65d)
 

# Add the IT – VLAN 10 and  Finance – VLAN 20 in the Firewall
![image](https://github.com/user-attachments/assets/289c564b-db84-4fca-ab4b-84b8ff2a4d85)
![image](https://github.com/user-attachments/assets/0db2d79c-ee23-44cc-b2ab-c653b671b644)
 
 
# Add the Rules and Policies for routing traffic in the Firewall
![image](https://github.com/user-attachments/assets/72b2de5c-51ae-432e-a5f6-5c60ef688aae)
![image](https://github.com/user-attachments/assets/790870ef-66ac-48f9-b2cb-ec225549fe2c)
![image](https://github.com/user-attachments/assets/2c69e52b-5096-4bb4-b721-6ea9a85038c1)
![image](https://github.com/user-attachments/assets/630be0eb-396c-4915-ae2e-772a9ab6105e)
![image](https://github.com/user-attachments/assets/8fe6c909-c823-4b00-b5ba-293c66c5f1d0)
![image](https://github.com/user-attachments/assets/b294bb29-79e1-4608-98dd-bd0e56fdf8ed)
![image](https://github.com/user-attachments/assets/0a8f18a5-b70f-4450-8ccb-57f3c40415f1)
 
 
 
# Add the Rules and Policies for routing internet traffic in the Firewall
![image](https://github.com/user-attachments/assets/1efa6c1c-b3f5-4e11-92c4-cb033efa0021)
![image](https://github.com/user-attachments/assets/6af7be01-810e-48f7-bddb-1e6fb04c98f1)
![image](https://github.com/user-attachments/assets/ff494835-6ceb-479e-ae4f-0cc8f25f02b0)
![image](https://github.com/user-attachments/assets/a84ddb48-9958-4fb4-926b-359ebca59b26)
![image](https://github.com/user-attachments/assets/5d0cabf0-e5fe-43fc-ac82-660b2893dc89)
 
 
 
 
 





