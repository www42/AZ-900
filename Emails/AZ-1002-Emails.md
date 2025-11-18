**Subject: General guidelines**
---
Some resources in this scenario might take several minutes to deploy. Please review the other tasks in the lab while the deployment completes. You may perform other tasks that do not rely on that deployment.

Thank you for agreeing to help our team configure secure access to your workloads using Azure networking.

We have some general guidelines that you must follow when you perform tasks in Azure.
* When creating objects, use the default settings unless a different configuration is required to complete the task successfully.
* Only create, delete, or modify objects to achieve the stated requirements. Unnecessary changes to the environment may adversely affect your final score.
* If there are multiple approaches to achieving a goal, always choose the approach that requires the least amount of administrative effort.
* A check box is provided in the header of each email so you can mark the tasks included in that email as complete. The check box is provided for your convenience; you are not required to select it. It is not used for scoring.

Thanks,
<br>
Chief Technology Officer (CTO)

<br>


**Subject: Existing environment**
---
Here are your credentials for accessing our Azure resources:

User name: 
<br>
Temporary Access Pass: 

You can also find the sign in information in the **Instructions** tab.

You have been given rights to the **RG1** resource group. Please create all Azure objects in this resource group.

Our Azure environment contains the following virtual networks in the West Europe Azure region.

| Name  | Subnet    | Virtual Machine
| ----- | --------- | ---------------
| VNet1 | Subnet1-1 | VM1
| VNet2 | Subnet2-1 | VM2  VM3

If you have any other questions about the environment, you can explore the Azure portal.

Thanks,
<br>
Network administrator

<br>


**Subject: Configure Subnet1-1 to use Azure Firewall**
---
Hello,

We want to start using Azure Firewall to control access from our Azure virtual networks to the internet.

Initially, Azure Firewall will be used for **Subnet1-1**. Hosts on **VNet1** will connect to a third-party internet app service named **RelecloudDataService**.
**RelecloudDataService** is accessible at **131.107.3.210** on **TCP port 9000**.

This is your task:

You need to deploy Azure Firewall and allow access from **Subnet1-1** to RelecloudDataService. Use a route table to ensure that all other access from **Subnet1-1** to the public internet is blocked.

Thanks,
<br>
Network administrator

<br>

**Subject: Prepare the environment for the deployment of VM4**
---
We are developing an application named App1 that will be provisioned on virtual machines in the West Europe and North Europe Azure regions. Initially App1 will be deployed to VM2 and VM3. Eventually, a new virtual machine named VM4 that will also host App1 will be deployed to the North Europe region.

This is your task:

You need to configure a subnet to support the deployment of **VM4**. The subnet must meet the following requirements:

* Be in the **North Europe** region.
* Use an IP address space of **10.3.1.0/24**.
* Ensure that the hosts on the new subnet can communicate with hosts on the same virtual network.
* Ensure that the new virtual network is peered with **VNet2**.

Thanks,
<br>
Application developer

<br>

**Subject: Configure DNS for the new subnet**
---
Hello,

I am providing the details for the DNS configuration on the subnet.

This is your task:

Configure DNS for the new subnet. Here are your requirements:

* Ensure that the hosts on the new subnet automatically register to an Azure Private DNS zone named **contoso.com**.
* Ensure that the hosts on the new subnet can connect to **VM2** on **Subnet2-1** by using the fully qualified name (FQDN) of **vm2.contoso.com**.

Thanks,
<br>
Application developer

<br>

**Subject: Configure network security**
---
We want to limit inbound traffic to **Subnet1-1**.

This is your task:

You need to create an application security group that contains **VM2** and **VM3**. Ensure that **Subnet1-1** only allows inbound connections from members of the application security group over **TCP port 1433**.

Thanks,
<br>
Security operations

<br>

**Subject: Status - Complete**
---
Thank you for helping our team configure and secure our Azure virtual networking environment.

We look forward to working with you again.

Regards,
<br>
Chief Technology Officer (CTO)
