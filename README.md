<p align="center">
<img src="Proton VPN.png"/>
</p>

<h1>Virtual Private Network (VPN) Setup and Usage</h1>
In this tutorial, we setup a VPN using Proton VPN and observe the changes of IP addresses from a personal PC to inside the VM. 
<h2>Video Demonstration</h2> 

- ### [VPN (Virtual Private Network) Explained](https://youtu.be/R-JUOpCgTZc)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Proton VPN

<h2>Operating Systems Used </h2>

- Windows 10 (22H2)

<h2>High-Level Steps</h2>

- Observe IP address for physical PC
- Observe IP address within VM (VPN **NOT** connected)
- Observe IP address within VM (VPN connected)

<h2>Actions and Observations</h2>

_⚠️**Before we start, if you haven't already, go ahead and create a **Microsoft Azure** and **Proton VPN** account on your physical PC**._


1️⃣First, we're going to create a VM in Azure running Windows 10 and select a region that is not our current (i.e. if you are in the US select Canada), then, in a new tab find our IP address (as it relates to country/region) by going to https://whatismyipaddress.com/ .
Locate **Remote Desktop** on your PC. We will use this to remote into our VM that we created earlier, by using the **Public IP** address. Do so now.


_Now the fun begins! Its great that you made it into the VM._


2️⃣ 
Now that we're inside the VM, open up a browser, go to https://protonvpn.com/ and login . Once logged in we are going to download the VPN Client for our operating system in use and begin the installation process and login.


_Almost there._


3️⃣ 
In the same browser, go to https://whatismyipaddress.com/ and observe your new IP address. What is the country/region?


_The good stuff._


4️⃣ 
Go back to your Proton VPN account and lets **connect** the VPN to place us in another location. There's a few options to choose from. Lastly, once connected go to https://whatismyipaddress.com/ and observe the IP address. Where are you now? 


Take a few moments to try going to some of your favorite websites, like Amazon, Netflix, or even Hulu while connected to the VPN. 
If you were following along, you saw that we started in the United States, launched our VM in Canada, then connected the VPN and landed in Tokyo, Japan.





<p align="center"> <img src="VPN Clients.jpg"/> </p>
<p>
New sentence here. Duhhhh...
</p>
<br />
# new image here
<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
New Sentence here. Duhhhhh...
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
New Sentence here. Duhhhhh...
</p>
<br />
