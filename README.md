<p align="center">
<img src="https://i.imgur.com/V3e1Tef.jpg" alt="Microsoft Active Directory Logo"/>
</p>

<h1>Remote Desktop (Azure)</h1>
This tutorial outlines remote desktop within Azure Virtual Machines.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop


<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)

<h2>Remote Desktop Configuration Steps</h2>

- Creating Resourse Group
- Creating Virtual Machine
- Locating IP Address
- Signing In

<h2>Deployment and Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/18qlsoJ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
</p>
<br />

<p>
<img src="https://i.imgur.com/4saEkDP.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
 <p>
<img src="https://i.imgur.com/C8ynA6l.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p> 
In order to remote desktop we first new to create a resource group. portal.azure.com -> type in resource group in the search menu. Once that's done hit resource group and create new. Select the region that works best for you, today we'll be using East US. Hit review and create and see if you pass validation. Once that's passed you have your resource group all created! 
</p>
<br />

<p>
<img src="https://i.imgur.com/N5Mu6yq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<p>
<img src="https://i.imgur.com/iL7kEqD.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Virtual Machines is going to be critical in today's lesson. Going back to your azure portal, go to the search and type in virtual machines. Select virtual machines and select create new. For the resource group, select the resource group that we created earlier. During the region make sure it's in the same region that you put the resource group in. Use a user name and password that you'll remember under the username and password section. The imagine tab will be what software you running and today we'll be running windows 10 (21H2). Select your size of the virtual machines and then select review + create.
</p>
<br />
<p>
<img src="https://i.imgur.com/LnVTaKq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<p>
<img src="https://i.imgur.com/CjmlDYn.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
 <p>
<img src="https://i.imgur.com/4qhmdwG.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

Now, that your virtual machines are created we need to grab the public IP address from it. In order to this go to virtual machines, select the one you created and copy the public IP address to your clipboard. Open up your start menu and type in "remote desktop connection". Remote Desktop Connection is up and you're going to paste the IP address that we copied earlier from our virtual machine. Sign in with the username and password you created in the virtual machine. Prompt should pop up after you've successfully logged in asking do you wish to continue. Select yes and you'll be connected to your remote desktop!
 <p>
<img src="https://i.imgur.com/Q3jOXSa.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<h2>You've successfully setup a remote desktop connection. Congrats!</h2>
