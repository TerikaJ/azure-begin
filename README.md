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
<img width="350" alt="Azure 1" src="https://github.com/TerikaJ/azure-begin/assets/136477450/58de82c1-b97d-447c-8fc6-1710a4f3e4e3">
</p>

- Click "Create" on the top left menu, OR simply click "Create resource group" in the center box (assuming one doesn't exist yet).
<p align="center">

<img width="350" alt="Azure 3" src="https://github.com/TerikaJ/azure-begin/assets/136477450/95963e84-c16a-4a2e-947d-a76b413526b5">

<img width="350" alt="Azure 2" src="https://github.com/TerikaJ/azure-begin/assets/136477450/e2f8d7b9-b8bc-4ae0-9848-2cda95a0e647">
</p>

- Name your "Resource group" anything you want (this example uses **RG-01**).
- Change the "Region" to a location that is closest to you (this example uses **(US) West US 3**).
- Skip through all other selections-- and click "Review + Create" on the lower left.
- You should see "Validation passed" on the next page.
- Click "Create".
<p align="center">

<img width="350" alt="Azure 4" src="https://github.com/TerikaJ/azure-begin/assets/136477450/bef6c948-b498-4f61-a1e6-e24a9297c12a">

<img width="350" alt="Azure 5" src="https://github.com/TerikaJ/azure-begin/assets/136477450/b8095fe1-fe73-464c-905a-8d6e45619e97">


</p><hr>

<h3>&#9314; Create a Storage Account</h3>

- In the "Search" box at the top header, type and select "Storage accounts" from the drop down.
  - If you see "Storage accounts" already listed on the home page, you can simply click the icon link, rather than performing a manual search.
<p align="center">

<img width="350" alt="Azure 6" src="https://github.com/TerikaJ/azure-begin/assets/136477450/69fd708f-548a-4d28-9ae2-a6555ed6e209">
<img width="350" alt="Azure 7" src="https://github.com/TerikaJ/azure-begin/assets/136477450/935516f8-b468-4491-bc80-9e8c446fa751">

</p>

- Click on "Create Storage account".
<p align="center">

<img width="350" alt="Azure 8" src="https://github.com/TerikaJ/azure-begin/assets/136477450/5bb54a8f-b006-4def-b846-4b9c6e43adf0">

</p>

- Use the same resource group that was just created (this example uses **RG-01**).
- Create a unique name for the storage account that hasn't already been taken (this example uses **saname01**).
- Choose the same region (this example uses **(US) West US 3**.
- Skip through all other selections and click "Review", then "Create".
<p align="center">

<img width="350" alt="Azure 9" src="https://github.com/TerikaJ/azure-begin/assets/136477450/0c656e1d-f9db-42ca-a185-40b22eeb32bb">

<img width="350" alt="Azure 10" src="https://github.com/TerikaJ/azure-begin/assets/136477450/b522ba67-78e1-46eb-b479-cdef7894c1de">

</p><hr>

<h3>&#9315; Create a Virtual Machine</h3>
     
- In the Search Box at the top header, type and select "Virtual machines" from the drop down.
  - If "Virtual machines" is already listed on the front page, you can simply click the icon link, rather than performing a manual search.
<p align="center">

<img width="350" alt="Azure 11" src="https://github.com/TerikaJ/azure-begin/assets/136477450/9c5280b3-1dae-437f-89bd-ec99f01a9167">

<img width="350" alt="Azure 12" src="https://github.com/TerikaJ/azure-begin/assets/136477450/a884bfc6-d3f4-4d11-8392-a225e8c86b1c">

</p>

- Click "Create", then select "Azure Virtual Machine"
<p align="center">

<img width="350" alt="Azure 13" src="https://github.com/TerikaJ/azure-begin/assets/136477450/cb3d3d84-3348-4b92-b53e-6bb939a46002">

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

<img width="350" alt="Azure 14" src="https://github.com/TerikaJ/azure-begin/assets/136477450/f44d0788-a591-49d9-9b27-c95635a6a293">
<img src="https://i.imgur.com/mcix7TW.jpg" height="50%" width="50%" alt="Azure Step 4-4"/>
<img width="350" alt="Azure 15" src="https://github.com/TerikaJ/azure-begin/assets/136477450/eebf668e-0dfc-4c6d-9a7f-fa23234d6efc">

</p><hr>

<h3>&#9316; Connect to the Virtual Machine via Remote Desktop</h3>

- Navigate to your most recently created Virtual Machine and COPY the machine's public IP address (located on the right side).
<p align="center">

<img width="450" alt="Azure 16" src="https://github.com/TerikaJ/azure-begin/assets/136477450/fc9296f5-b84e-432c-a07e-10c2c3486464">


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

<img width="350" alt="Azure 17" src="https://github.com/TerikaJ/azure-begin/assets/136477450/a0b4dcab-67e7-4857-95d3-328ffd2001a5">
<img width="350" alt="Azure 18" src="https://github.com/TerikaJ/azure-begin/assets/136477450/849ed342-9211-4c1f-b96e-aa774ec0657b">
<img width="350" alt="Azure 19" src="https://github.com/TerikaJ/azure-begin/assets/136477450/5ea2925a-f9e6-4d10-9de2-4ebdb81f5b9b">
<img width="350" alt="Azure 20" src="https://github.com/TerikaJ/azure-begin/assets/136477450/96e37bab-b165-4f32-ae75-2de062754870">
<img width="350" alt="Azure 21" src="https://github.com/TerikaJ/azure-begin/assets/136477450/8652ccbf-b272-4390-b526-2fcd4106305a">
</p>
  
- Double-click on the virtual machine, then enter the username and password from Step 4.
- Select "Continue".
- A prompt will appear that mentions "the identity cannot be verified;" continue and press "YES".
<p align="center">
<img src="https://i.imgur.com/3YxlS2G.jpg" height="64%" width="64%" alt="Azure Step 5-3"/>
</p>

- Toggle the settings you want, then click "Accept".
<p align="center">
<img width="350" alt="Azure 22" src="https://github.com/TerikaJ/azure-begin/assets/136477450/561cf5ae-2df5-4c2c-a8f1-6e06c1ef3fe3">

</p>

🎊 CONGRATULATIONS! You've created your very first virtual machine within Microsoft Azure! 🎊
<p align="center">

<img width="350" alt="Azure 23" src="https://github.com/TerikaJ/azure-begin/assets/136477450/71568840-b6c3-40d7-b921-9006c398c8a8">

</p>
<hr>

<h3>BONUS: Delete All Resources In Azure</h3>

_To retain your free remaining Azure credits, we must ensure that we DELETE ALL of our resources after every project._
- From Azure, navigate to "Resource Groups", select any Resource listed, then click "Delete resource group".
- Type the resource group name to confirm deletion (faster to copy/paste the name).
- Then click "Delete".
_Repeat these steps for every resource group listed until all resources are deleted_
<p align="center">

<img width="350" alt="Azure 24" src="https://github.com/TerikaJ/azure-begin/assets/136477450/99a55bef-235e-4e84-9546-9ca64648437d">
<img width="350" alt="Azure 25" src="https://github.com/TerikaJ/azure-begin/assets/136477450/25e2d343-dc99-4560-9ced-e70e75390efd">
<img width="350" alt="Azure 26" src="https://github.com/TerikaJ/azure-begin/assets/136477450/f06afeb6-8c41-4233-a92a-112c606aef9b">

</p>
  
_If you have remaining virtual machines:_
- From Azure, navigate to "Virtual Machines", select any that are listed, then click "Delete".
- Checkmark the box "I have read and understand..."
- Then click "Delete".
_Repeat these steps until all listed machines and supporting applications are deleted._
<p align="center">

<img width="350" alt="Azure 27" src="https://github.com/TerikaJ/azure-begin/assets/136477450/a7c7af43-899f-425e-b6ce-9512744c0973">

</p>

_The best way to ensure all resources are removed is by navigating to "All resources" located on the Portal Home page to verify deletion._
<p align="center">

<img width="350" alt="Azure 28" src="https://github.com/TerikaJ/azure-begin/assets/136477450/741dbf7c-e180-4c42-8ed1-2229107bad72">

</p>
  
<h1><p align=center> Done! Good job! </p></h1>

<h2><p align=center> The Next Demonstration:<br><a href="https://github.com/terikaj/configure-ad">Configuring Active Directory within an Azure Virtual Machine</a></p></h2>
