# DHCP
Configuration of IP address on new end devices

https://github.com/LandonGomes/DHCP/assets/146256868/544d8a7e-f803-4840-8dd4-6a3bfc289333

<h2>Configuration Steps</h2>

</p>
</p>

Step 1) Select your end devices (PC desktops and printer)
Step 2) Select your cabling for you devices, connecting to the DHCP enabled router, be mindful what ports are used. *Note recommended that you follow some sort of order.*
Step 3) Right click your first PC, select IpConfig. On this screen you'll notice that Static is selected which would mean the admin would have to configure this PC manually. Click DHCP
Step 4) When DHCP is selected all information in the IPv4 section as become automatically selected and assigned. Looking at the IPv4 address we can see that the host is .100 and the default gateway is 192.168.0.1. *IPv6 was not changed due to remaining in a static mode.*
Step 5) Write down the default gateway 192.168.0.1
Step 6) Close out of IP Configuration and open Web browser and enter 192.168.0.1. Once prompt to enter username: admin password: admin
Step 7) Scrolling through you'll notice that the start IP address 192.168.0.100 is the first available address with 50 additional users (addresses).
Step 9) Repeat steps for other end devices, check each IP address and you'll notice each IPv4 address host should increase by 1 increment.

Thanks,
Landon
