<p align="center">
<img src="https://i.imgur.com/zpnbAJr.png" alt="VPN Traffic"/>
</p>


# 


<h1> Observing VPN traffic within an Azure Virtual Machine </h1>
In this tutorial, we will create a windows vm within Azure and observe how a VPN affects the IP address. <br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- A VPN (Proton VPN)

<h2>Operating Systems Used </h2>

- Windows 10

<h2>List of Prerequisites</h2>

- Create an Azure Account (free)


<h2>High-Level Steps</h2>

- STEP 1 - Locate Your Machines Local IP
- STEP 2 - Set Up VM Using Azure
- STEP 3 - Locating IP Through VM 
- STEP 4 - Setup VPN
- STEP 5 - Connecting to VPN Through VM
- STEP 6 - Locating IP Through VPN 

<h2>Instillation Steps</h2>
<p> STEP 1 - Locate your IP address by going to "www.whatismyipaddress.com". We will use this later as well. See the screenshot below.</p>

<p>
<img src="https://i.imgur.com/OusKcih.png"/>
</p>

<p> Step 2 - Set Up VM Using Azure</p>
 <p>Go to www.portal.azure.com and find Virtual Machines.   See the screenshot below.</p>
</p>
<p>
<img src="https://i.imgur.com/DRGwczk.png"/>
</p>

<p>
Click the "Create -> Azure Virtual Machine" button to begin creating the VM. Create a new Resource Group for the VM. Name your VM. Choose an availability zone that allows you to create an instance. I choose Zone 2. See the screenshot below.  
</p>

<p>
<img src="https://i.imgur.com/wUW2Kgi.png"/>
</p>

<p>
  Choose a Windows 10 as your Image. For the size, 2 vcpus and 4GB will do.
</p>

<p>
<img src="https://i.imgur.com/IscBjnC.png"/>
</p>

<p>
  For the Username and Password you can create your custom information, just record it personally. Then select “Review and Create”, once it passes validation select “Create” at the bottom.
</p>

<p>
<img src="https://i.imgur.com/Z5dmmm6.png"/>
</p>
<br />

<p> Step 3 - Locating IP Through VM </p>
<p> Now that we have set up the Virtual Machine we will be connecting to it using the application “Remote Desktop Connection” or RDP. We will input the IP address for the VM that was assigned after we created the VM (see 1st screenshot below) and then input the credentials we set when creating the VM. (see 2nd screenshot) </p>

<p>
<img src="https://i.imgur.com/GYz4vSd.png"/>
</p>

<p>
<img src="https://i.imgur.com/IZvQ9g7.png"/>
</p>


<p>Once logged in, we will open the web browser and again look up www.whatismyipaddress.com. </p>

<p>
<img src="https://i.imgur.com/gNYpFFR.png"/>
</p>

<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
