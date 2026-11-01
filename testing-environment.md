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
-Get IPv4 address. default gateway, and DNS server addresses  
-Rt click Properties  
-Select IPVv4  
-Select "Use the following IP address"  
-Select "Use the following DNS server address"  
-Refresh server  
-AUTOMATIC IP ADDRESS ASSIGNMENT ON CLIENT COMPUTERS IS FINE  
firewall

TEST CONNECTIVITY  
-Open command prompt on server and ping client (ping xxx.xxx.xxx.xxx) or by  computer name  
-If connectivity fails, disable windows firewall on the client computers  '
-On client computer, go to Control Panel, Windows Defender Firewall, Turn Windows Defender on or off, select 'Turn off Windows Defender Firewall'  
-From server, 'Manage', 'Windows Defender Firewall with Advanced Security'
-Rt click on first option, Properties, 'Firewall State' to off in Domain Profile (from within 'Public Profile' tab as well)  
-Apply, OK  
-Test by opening command prompt in client and ping server IP  address


