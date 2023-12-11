# Azure Resource Group and Virtual Machine Set-up

# ![image](https://github.com/Meeksaint/Azure-Virtual-Machine/assets/150755308/b21de015-743d-4d9b-be87-8eff4c33cd35)

<p align="center">

</p> 

<h1>Microsoft Azure Virtual Machine </h1>
This tutorial outlines a thorough series of steps on how to create a resource group and setup a virtual machine in Microsoft Azure and how to connect the VM with Remote Desktop connection.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Resource group/Virtual Machines/Compute)
- Remote Connection

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

<h> </h>

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

<h2> </h2>



<h2>Installation Steps For Virtual Machine</h2>

- Step 1: Open Azure dashboard

![image](https://github.com/Meeksaint/Azure-Virtual-Machine/assets/150755308/f1ad0337-8e96-46dc-a205-5af64865bce7)

In the dashboard section, click on the virtual machine icon (indicated by the short arrow), or type "virtual machine" in the search bar (indicated by the long arrow).

- Step 2: Select basic VM option

![image](https://github.com/Meeksaint/Azure-Virtual-Machine/assets/150755308/4e10a994-3fbc-4bd6-ad0b-f25b941c0469)

Click on the first option (indicated by the arrow) "Azure virtual machine" to start creating and configuring a VM.

- Step 3: Configure the VM

![image](https://github.com/Meeksaint/Azure-Virtual-Machine/assets/150755308/f195094f-c5e3-4894-9186-93f07c2c442c)

This first half entails the storage of the virtual machine into a resource group, and since there has already been a resource group (AD-lab2023) created, the VM can be assigned to it. The other section demands that the virtual machine has a name, the name could be anything, however it's important that its name relates to the project (s) that the VM will be used for so as to better identify what service was deployed into it.

- Step 4: Select VM's Operating System and performance type

  ![image](https://github.com/Meeksaint/Azure-Virtual-Machine/assets/150755308/b77619a8-4306-4ab2-8b35-e42271cdd3cd)

  In the "image" section (indicated by the short arrow) that is where the various operating systems can be selected and deployed based on the services they provide. The section that says "size" (indicated by the long arrow) has to do with the performance of the VM. The least virtual cpu (vcpu) a VM has the less efficient it operates, however, the more virtual cpu a VM has makes it more efficient. For example: In the image shown there is a "Windows Server" operating system that is selected with 2 virtual cpu which provides more efficiency for the VM.

 - Step 5: Create username and password for VM
 
  ![image](https://github.com/Meeksaint/Azure-Virtual-Machine/assets/150755308/d0d126d6-2e2d-42e0-8ea5-3f4bfe3875d3)

Create a username for the VM and set and confirm a password that can be remembered which will be required upon the future use of the VM.

- Step 6: Agree to license for usage and advance

![image](https://github.com/Meeksaint/Azure-Virtual-Machine/assets/150755308/fa9104ac-7029-4da9-bf3c-d439e400f60c)

Accept the license to use the VM, then click on the "Next: Disks" prompt until advanced to the Networking section of the process.

- Step 7: Network Configuration

![image](https://github.com/Meeksaint/Azure-Virtual-Machine/assets/150755308/7b282fbe-55a7-4128-a88a-3b64484b942a)

The virtual network (vnet), the subnet, and the Public IP address has all been created by default by Azure network interface system, therefore there is no urgent need to create any other unless indispensible for further processes. After the network configuration has been finalized, click on the "Review + create" prompt to validate the settings and create the VM.

- Step 8: VM Validation status and final process

![image](https://github.com/Meeksaint/Azure-Virtual-Machine/assets/150755308/c6f7cd8c-4b70-4c8d-8857-f38e66294a9a)

Once the validation status is set to pass, click create (indicated by the arrow) to advance to the final processing phase.

- Step 9: VM completion process

![image](https://github.com/Meeksaint/Azure-Virtual-Machine/assets/150755308/8d3090f5-a21c-47f4-a227-257746e80f08)

The VM's operating system, IP address, vnet, subnet and more are being proccesed to be deployed.

- Step 10: VM is completed.

![image](https://github.com/Meeksaint/Azure-Virtual-Machine/assets/150755308/1665f14c-fedd-49c1-a3c2-d38f429b34a0)

All the resources and tools in the virtual machine is completed and ready to be deployed.

- Step 11: View the virtual machine on dashboard

![image](https://github.com/Meeksaint/Azure-Virtual-Machine/assets/150755308/abd7ba33-6663-488d-bcf4-afe9df1404aa)

Once the VM has been created, it can be seen on Azure dashboard section (indicated by short arrow), and if wishing to use another method of locating the VM, click on the "Virtual Machine" icon (indicated by the long arrow) to view more details about the VM.

 - Step 12: Access Virtual Machine from within resource group

![image](https://github.com/Meeksaint/Azure-Virtual-Machine/assets/150755308/5a0eb687-d5ef-443b-8012-c63147879633)

The section shows the VM and its resource components inside of the resource group (indicated by the short arrow). The VM (indicated by the long arow) can be accessed by clicking on the icon at the virtual machine category.

- Step 13: Virtual Machine Network Information

![image](https://github.com/Meeksaint/Azure-Virtual-Machine/assets/150755308/60ecf2f8-77e7-4149-a317-48b72c07c5de)

The network settings and configurations such as the Public/Private IP address, Vnet/Subnet, Operating System used, and more can be found within the VM section (indicated by the arrow)





<h2> Remote Desktop Connection Setup </h2>

- Step 1: Copy Public IP address from VM

![image](https://github.com/Meeksaint/Azure-Virtual-Machine/assets/150755308/b660dd7e-9f08-496c-94f3-525ee61c8242)

The VM public IP address is prerequisite in establishing a remote connection. 

- Step 2: Open Remote Desktop Connection Application

![image](https://github.com/Meeksaint/Azure-Virtual-Machine/assets/150755308/8d5aba88-9948-46ec-98df-3cbebd5abfe9)

To open the Remote Desktop Connection app, click on the Windows explorer icon and in the search bar type "Remote Desktop Connection



