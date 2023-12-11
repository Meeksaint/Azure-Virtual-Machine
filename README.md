# Azure Resource Group and Virtual Machine Set-up

# ![image](https://github.com/Meeksaint/Azure-Virtual-Machine/assets/150755308/b21de015-743d-4d9b-be87-8eff4c33cd35)

<p align="center">

</p> 

<h1>Microsoft Azure Virtual Machine </h1>
This tutorial outlines a thorough series of steps on how to create a resource group and setup a virtual machine in Microsoft Azure and how to connect the VM with Remote Desktop connection.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)




<h2>Installation Steps For Resource Group</h2>

- Step 1: Open Azure dashboard


![image](https://github.com/Meeksaint/Azure-Virtual-Machine/assets/150755308/2a0dc0a9-1e74-4925-a2b6-8e45ba189ed8)


In the dashboard section there are various tools and services, however before a virtual machine (VM) is established, a Resource group is prerequisite. It can be created by clicking on the icon (indicated by the short arrow), or type "resource group" in the search bar (indicated by the long arrow).

- Step 2: Create Resource group

![image](https://github.com/Meeksaint/Azure-Virtual-Machine/assets/150755308/a1c9382f-b975-473e-a3a4-383f5c36bfaa)


In this section, there are two options to choose from to start creating a resource group. Whether the option (indidated by the the short arrow, or the option indicated by the long arrow) is selected, they both lead to the same page on creating a resource group.


- Step 3: Name the resource group and select region to complete the set up

![image](https://github.com/Meeksaint/Azure-Virtual-Machine/assets/150755308/0bcf6090-2168-49b0-9dc8-dc47b90e8dbe)

The section (indicated by the short arrow) is what the resource group should be named. It can be named anything, however it would be ideal that the name of the resource group aligns with the content (s) that will be stored into it to be more organised. For example: In the resource group on the image shown, it is named "AD-lab2023" because a lab with Active Directory configuration will be conducted and stored inside of the resource group so that the lab can be easily identifiable as to which resource group is belongs to. The region section (indicated by the long arrow) is where the resource group is being created, that is whichever region of the world the resource group is being created, select accordingly. Afterwhich, click on "Review + create" (in the bottom left corner) to finish setting up the resource group.
</p>

- Step 4: Validation status and creation of resource group


![image](https://github.com/Meeksaint/Azure-Virtual-Machine/assets/150755308/d1186480-0fc4-457a-950c-275d26b55bd3)

</p>
<p>
Once the resource group validation status is set to pass, click on the "create" button to finalize the setup.
</p>
<br />

- Step 5: View resource group on dashboard

![image](https://github.com/Meeksaint/Azure-Virtual-Machine/assets/150755308/02b3283f-4b14-47a9-9bd0-b0ef744a4c34)


After completion of the resource group, it will be shown on the dashboard (indicated by the short arrow) that it was created. Another way to know if it was created is to click on the resource group icon (indicated by the long arrow) which is where the group is located.




<h2>Installation Steps For Virtual Machine</h2>
