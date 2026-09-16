Home Network Setup - Wireless Router and Client Configuration
Cisco Packet Tracer lab from Module 4.4 (Set Up a Home Router) of my Cisco Networking Basics course. The task was to wire up a small home network, configure a wireless router, and connect both wired and wireless devices to the internet.

Scenario
A new house needs to be connected to the cable provider's network for TV and internet, and the home network needs to support two wired PCs and one wireless laptop.

Devices used
Cable Splitter
Cable Modem
TV
Home Wireless Router
Office PC (wired)
Bedroom PC (wired)
Laptop (wireless)

Part 1: Cabling
Ran coaxial cable from the splitter to the cable modem, and from the splitter to the TV.
Confirmed the coax connections were correct by turning the TV on and checking for a picture.
Connected the cable modem to the router's Internet port with an Ethernet cable.
Connected the Office PC and Bedroom PC to the router's LAN ports with Ethernet cables.

Part 2: Router configuration
Logged into the router's web interface from the Office PC and configured:
Max DHCP users set to 10
Default admin password changed to MyPassword1!
2.4 GHz wireless enabled
SSID set to MyHome
Security set to WPA2-Personal with passphrase MyPassPhrase1!

Part 3: Client setup and testing
Connected the laptop to the MyHome wireless network using the passphrase, confirmed it got an IP address from DHCP, and loaded the test page skillsforall.srv.
Confirmed the Office PC had internet access by loading the same test page.
Set the Bedroom PC to DHCP, confirmed it got an IP address, and confirmed internet access.
Result

All three devices - two wired, one wireless - successfully connected to the network and reached the internet.

What I learned

How a home network is physically wired from the ISP connection down to individual devices, how to configure a wireless router through its admin interface, and why basic security steps like changing default passwords and enabling WPA2 matter.

---

### 🔑 Key Concepts This Reinforced
- Default credentials are a real security risk — changing the router's admin password is one of the simplest but most important first steps in securing any network
- WPA2 Personal is currently a baseline standard for home wireless security, not an optional extra
- DHCP failures (like the laptop showing 0.0.0.0) are common in real networks, and knowing how to force a renewal is a practical troubleshooting skill, not just a Packet Tracer quirk.