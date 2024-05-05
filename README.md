<p align="center">
<img src="assets/multi-site-vpn-logo.svg" width="400px" alt="Multi-Site VPN Logo" />
</p>

# Multi-site VPN and VoIP Integration to Reduce Interoffice Communication Costs
This project addressed communication challenges faced by a real estate management company with one main office and six satellite offices. Previously, satellite offices relied on traditional phone lines for interoffice communication, leading to high monthly costs. To overcome this, a new multi-site VPN tunnel was established to allow voice traffic alongside existing data traffic. Additionally, IP phones were deployed at satellite locations, leveraging existing infrastructure and significantly reducing operating costs.

## Environments and Technologies Used

- Sonic Wall TZ 170

## Operating Systems Used
- Windows 8.1 Professional

- Operating System Name

## High-Level Deployment and Configuration Steps

- Create address objects for each satellite office's LAN network, voice network, and WAN IP address in the main office firewall
- Create address objects for the main office's LAN network, voice network, and WAN IP address in each satellite office's firewall
- Create the VPN policy in the main and all satellite office firewalls
- Create static routes in the main and all satellite office firewalls
- Enable the the VPN and test communication on the voice and data networks
- Deploy and configure IP phones at satellite offices replacing traditional phone lines

<h2>Architecture Diagram</h2>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
