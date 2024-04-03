<p align="center">
<img src="https://i.imgur.com/1DDZ4Ui.png" height="50%" width="50%" alt="Microsoft Azure Logo"/>
</p>
<p align="justify">
<h1>Microsoft Azure</h1>

This demonstration will show how to do the following:
  - Setup a FREE* Azure account
  - Create a Resource Group
  - Create a Storage Account
  - Create a Virtual Machine (VM)
  - Connect to the VM using Remote Desktop

<h2>Requirements</h2>

- Computer w/ Internet Connection
- Credit Card (Required for free Azure credits)
- Remote Desktop Connection (Windows) / Microsoft Remote Desktop (Mac)
  
<h2>Step Process</h2>

<h3>&#9312; Create a FREE* Azure Account</h3>

Go to [https://azure.microsoft.com/en-us/free/](https://azure.microsoft.com/en-us/free/)
- Click "Start Free".
- Follow the prompt to create an account.
  - You WILL need to provide your credit card information to receive the free $200 Azure credits!
    <div> Azure will not charge you, <b>however, please keep in mind the credits are only accessible for 30 days!</b>
- Once you've completed the sign-up portion, click on <a href="https://portal.azure.com/">Go to the Azure Portal (portal.azure.com)</a>.
<p align="center">
<img src="https://i.imgur.com/FklBT6F.jpg" height="64%" width="64%" alt="Azure Free Account"/>
</p><hr>

<h3>&#9313; Create a Resource Group</h3>

- In the Search Box at the top header, type "Resource groups" and select the name from the drop down menu.
  - If you find that "Resource groups" is already listed on the home page, you can simply click the icon link, rather than performing a manual search.
<p align="center">
<img src="https://i.imgur.com/gza489d.jpg" height="64%" width="64%" alt="Azure Step 2-1"/>
</p>

- Click "Create" on the top left menu, OR simply click "Create resource group" in the center box (assuming one doesn't exist yet).
<p align="center">
<img src="https://i.imgur.com/5Jo1cEg.jpg" height="64%" width="64%" alt="Azure Step 2-2"/>
</p>

- Name your "Resource group" anything you want (this example uses **RG-01**).
- Change the "Region" to a location that is closest to you (this example uses **(US) West US 3**).
- Skip through all other selections-- and click "Review + Create" on the lower left.
- You should see "Validation passed" on the next page.
- Click "Create".
<p align="center">
<img src="https://i.imgur.com/BSiQM05.jpg" height="100%" width="100%" alt="Azure Step 2-3"/>
</p><hr>

<h3>&#9314; Create a Storage Account</h3>

- In the "Search" box at the top header, type and select "Storage accounts" from the drop down.
  - If you see "Storage accounts" already listed on the home page, you can simply click the icon link, rather than performing a manual search.
<p align="center">
<img src="https://i.imgur.com/HMUaR98.jpg" height="70%" width="70%" alt="Azure Step 3-1"/>
</p>

- Click on "Create Storage account".
<p align="center">
<img src="https://i.imgur.com/sGDY2Im.jpg" height="70%" width="70%" alt="Azure Step 3-2"/>
</p>

- Use the same resource group that was just created (this example uses **RG-01**).
- Create a unique name for the storage account that hasn't already been taken (this example uses **saname01**).
- Choose the same region (this example uses **(US) West US 3**.
- Skip through all other selections and click "Review", then "Create".
<p align="center">
<img src="https://i.imgur.com/07sG8Z6.jpg" height="100%" width="100%" alt="Azure Step 3-3"/>
</p><hr>

<h3>&#9315; Create a Virtual Machine</h3>
     
- In the Search Box at the top header, type and select "Virtual machines" from the drop down.
  - If "Virtual machines" is already listed on the front page, you can simply click the icon link, rather than performing a manual search.
<p align="center">
<img src="https://i.imgur.com/6DdH3MD.jpg" height="70%" width="70%" alt="Azure Step 4-1"/>
</p>

- Click "Create", then select "Azure Virtual Machine"
<p align="center">
<img src="https://i.imgur.com/tiC5aA4.jpg" height="70%" width="70%" alt="Azure Step 4-2"/>
</p>

- Use the same resource group (this example uses **RG-01**)
- Name your virtual machine however you want (this example uses **virtualmachine01**)
- Use the same region (this example uses **(US) West US 3**)
- Choose your "Image" (this example uses **Windows 10 Pro, version 22H2 - x64 Gen2**)
- Choose a "Size" (this example uses **Standard_E2s_v3 - 2 vcpus, 16 GiB memory**)
- Create any username and password of your choice (this example uses the username: **vmuser**)
  - Be sure to write down your login credentials (username/password), either on a notepad or utilize the "stickies" application within your PC or Mac.
- Check the "Licensing" checkbox.
- Click "Review + create".
  - After validation passed, click "Create".
<p align="center">
<img src="https://i.imgur.com/UaviYRo.jpg" height="70%" width="70%" alt="Azure Step 4-3"/>
<img src="https://i.imgur.com/mcix7TW.jpg" height="70%" width="70%" alt="Azure Step 4-4"/>
</p><hr>

<h3>&#9316; Connect to the Virtual Machine via Remote Desktop</h3>

- Navigate to your most recently created Virtual Machine and COPY the machine's public IP address (located on the right side).
<p align="center">
<img src="https://i.imgur.com/Cr02uvs.jpg" height="100%" width="100%" alt="Azure Step 5-1"/>
</p>

- Press the Windows Key (or Start Button), then select "Remote Desktop Connection".
- Input the virtual machine's Public IP Address and click "Connect".
- Enter the username and password (copy from your notepad) in Step 4, then click "OK".
  
<p align="center">
<img src="https://i.imgur.com/rP1uKCe.jpg" height="64%" width="64%" alt="Azure Step 5-2"/>
</p>

- Macintosh users begin here:
  - Download "Microsoft Remote Desktop" from the application store, and Open it.
- Click "Add PC", input the public IP address, then select "Add".
<p align="center">
<img src="https://i.imgur.com/ZhWBhLs.png" height="50%" width="50%" alt="Azure Step 5-2-1"/>
<img src="https://i.imgur.com/Mx1gHxa.png" height="50%" width="50%" alt="Azure Step 5-2-2"/>
</p>
  
- Double-click on the virtual machine, then enter the username and password from Step 4.
- Select "Continue".
- A prompt will appear that mentions "the identity cannot be verified;" continue and press "YES".
<p align="center">
<img src="https://i.imgur.com/3YxlS2G.jpg" height="64%" width="64%" alt="Azure Step 5-3"/>
</p>

- Toggle the settings you want, then click "Accept".
<p align="center">
<img src="https://i.imgur.com/VlNH4O9.jpg" height="50%" width="50%" alt="Azure Step 5-4"/>
</p>

🎊 CONGRATULATIONS! You have created your very first virtual machine within Microsoft Azure! 🎊
<p align="center">
<img src="https://i.imgur.com/PpLmQO7.jpg" height="80%" width="80%" alt="Azure Step 5-5"/>
</p>
<hr>

<h3>BONUS: Delete All Resources In Azure</h3>

_To retain your free remaining Azure credits, we must ensure that we DELETE ALL of our resources after every project._
- From Azure, navigate to "Resource Groups", select any Resource listed, then click "Delete resource group".
- Type the resource group name to confirm deletion (faster to copy/paste the name).
- Then click "Delete".
_Repeat these steps for every resource group listed until all resources are deleted_
<p align="center">
<img src="https://i.imgur.com/Yedg9Cl.jpg" height="80%" width="80%" alt="Azure Step 5-5"/>
</p>
  
_If you have remaining virtual machines:_
- From Azure, navigate to "Virtual Machines", select any that are listed, then click "Delete".
- Checkmark the box "I have read and understand..."
- Then click "Delete".
_Repeat these steps until all listed machines and supporting applications are deleted._
<p align="center">
<img src="https://i.imgur.com/T8VFNCO.jpg" height="80%" width="80%" alt="Azure Step 5-5"/>
<img src="https://i.imgur.com/dkuz7TD.jpg" height="80%" width="80%" alt="Azure Step 5-5"/>
</p>

_The best way to ensure all resources are removed is by navigating to "All resources" located on the Portal Home page to verify deletion._
<p align="center">
<img src="https://i.imgur.com/gVnbWJS.jpg" height="80%" width="80%" alt="Azure Step 5-5"/>
</p>
  
<h1><p align=center> Done! Good job! </p></h1>

<h2><p align=center> Our Next Demonstration:<br><a href="https://github.com/terikaj/configure-ad">Configuring Active Directory within an Azure Virtual Machine</a></p></h2>
