**Windows Networking Lab**

I configured static IPv4 and DNS settings on a Windows virtual machine and then validated connectivity using built-in Windows networking tools. This shows a structured networking workflow for configuration, verification, and troubleshooting.

Objectives

- Configure static IPv4 settings in a Windows virtual machine
- Assign and review DNS settings
- Validate adapter properties and network interface details
- Verify local and external connectivity using Command Prompt
- Confirm DNS resolution and route visibility using built-in Windows networking tools

Static IP Configuration

I configured a static IPv4 address, subnet mask, gateway, and preferred DNS values in Windows network settings. This shows manual network assignment for controlled network communication.

<img src="images/Edit IP settings.png" alt="Static IP Configuration" width="700"/>

DNS Configuration

I reviewed DNS settings and confirmed local DNS assignment using loopback resolution. This shows how DNS is manually defined in a Windows environment.

<img src="images/Edit DNS settings.png" alt="DNS Configuration" width="700"/>
Network Adapter Review

I reviewed adapter properties to confirm interface details, link speed, MAC address, and assigned IPv4 values. This shows hardware-level visibility of the active network adapter.

<img src="images/Network adapter details.png" alt="Network Adapter Details" width="700"/>

Full Configuration Validation

I ran ipconfig /all in Command Prompt to verify active IP settings, DNS servers, gateway values, and adapter details. This shows command-line validation of the full network configuration.

<img src="images/Command prompt ipconfig all.png" alt="IP Configuration" width="700"/>

Gateway Connectivity Test

I ran ping against the default gateway to confirm successful communication with the local router.

<img src="images/Command prompt ping.png" alt="Ping Gateway" width="700"/>

External Connectivity Test

I ran ping against google.com to confirm hostname resolution and external internet connectivity.

<img src="images/Command prompt ping google.png" alt="Ping Google" width="700"/>

Route Visibility Test

I ran `tracert` against google.com to view network hops between the virtual machine and the external destination.

<img src="images/tracert google.png" alt="Trace Route" width="700"/>

DNS Resolution Test

I ran `nslookup` against google.com to confirm DNS name resolution and returned address information.

<img src="images/nslookup google.png" alt="NSLookup" width="700"/>

Summary

This lab shows a structured Windows networking workflow using both graphical settings and command-line validation. I manually configured IP and DNS values, reviewed adapter properties, confirmed gateway communication, tested external connectivity, verified route visibility, and confirmed DNS resolution. This reflects a practical approach to network verification and basic troubleshooting in a Windows environment.

Navigation

[`Back to GitHub Profile`](https://www.github.com/cbueker-it)
