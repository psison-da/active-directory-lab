Server name change:  

  From within server"  
  
  -Click "Computer Name"(leave workgroup as is)  
  
  -Click "Change"
  -Reboot  
  

  From client computers:
  -Rt Click windows icon
  -Click "System"
  -Click "Rename this PC" or under related links "Domain or workgroup"

From server(change IP address to static IP):
-Click "assigned by DHCP" in Ethernet0
-Click "Details"
- Get IPv4 address. default gateway, and DNS server addresses
-Rt click Properties
-Select IPVv4
-Select "Use the following IP address"
-Select "Use the following DNS server address"
-Refresh server
-AUTOMATIC IP ADDRESS ASSIGNMENT ON CLIENT COMPUTERS IS FINE

