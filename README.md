<p align="center">
<img src="https://github.com/ronnydiggs/vpn/assets/64152064/aa32145e-bac6-4fc2-b426-2a2a981321bd" width="250"/>
</p>

<h1>Virtual Private Network - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the VPN lab. 
<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Proton VPN
- Remote Desktop
- Client 1 VM
  

<h2>Operating System Used </h2>

- Windows 10 Pro</b>

<h2>How VPN works</h2>
<p>
<img src="https://github.com/ronnydiggs/vpn/assets/64152064/64532233-942a-457d-993b-2d627f1452ba" width="600"/>
</p>
<br />

<h2>Create the Virtual Machine</h2>

<p>
<img src="https://github.com/ronnydiggs/azure-network-protocols/assets/64152064/745f66ae-390d-4e57-969b-c58a8018bd0f" width="400"/>
</p>
<p>
Make sure both VMs are created on the same vnet and resource group.
Log into Client 1 (4.227.147.96) through RDP.
</p>
<p>
Note the private IP address for the Windows client as: 10.0.0.4.
</p>
<br />

<h2>Test the Public IP of VM</h2>
<p>
<img src="https://github.com/ronnydiggs/vpn/assets/64152064/dd3231bd-c60b-4917-a3d8-3670967985ca" width="800"/>
</p>
<p>
Go to https://whatismyipaddress.com/ and test the IP of the VM. Notice the IP is the same as the VM.
</p>
<br />

<h2>Test the Public IP with Proton VPN</h2>
<p>
<img src="https://github.com/ronnydiggs/vpn/assets/64152064/8f4368de-1302-47b0-8366-aa6ce8ea6ba7" width="800"/>
<img src="" width="400"/>
</p>
<p>
Proton VPN establishes a secure tunnel between the client, the internet, and its intended destination. The VPN client encrypts the connection through the ISP to the VPN server  where the VPN server can send data through the secure encrpyted tunnel to the internet and back to the client.
</p>
<br />




