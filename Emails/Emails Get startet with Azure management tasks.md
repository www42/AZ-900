**Subject: General guidelines**
---
Our application developers need help managing test environments in Azure. The test environments include Azure resources such as storage accounts, virtual
machines, virtual networks and Al services. We need you to perform basic management tasks of these resources.

We have some general guidelines that you must follow when you perform tasks in Azure. Please always use the following guidelines:
* When creating objects, use the default settings unless a different configuration is required to complete the task successfully.
* Only create, delete, or modify objects to achieve the stated requirements. Unnecessary changes to the environment can adversely affect your final score.
* If there are multiple approaches to achieving a goal, always choose the approach that requires the least amount of administrative effort.
* A check box is provided in the header of each email so you can mark the tasks included in that email as complete. The check box is provided for your convenience; you are not required to select it. It is not used for scoring.

Thanks,
<br>
Chief Technology Officer (CTO)

<br>


**Subject: Existing environment**
---
Here are your credentials for accessing our resources in Azure:

    User name: 
    Temporary Access Pass: 

You can find these credentials by clicking the Instructions tab.

On your desktop, you will find the Contoso Data Editor app. Please use this app when documenting our environment.

Thanks,
<br>
Network administrator

<br>


**Subject: Manage virtual networking**
---
Hello,

Our developers have Azure virtual machines and virtual networks that they use for testing. The developers have requested configuration changes to these resources.
They also need information about the current configuration of several virtual machines.

This is your task:

You need to perform the following tasks:
* Start the VM1 virtual machine.
* Assign the NSG1 network security group (NSG) to the network interface associated to VM1.
* Configure VM2 to turn off automatically at 1:00:00 AM (UTC-6:00) Central America.

You also need to gather some missing information about the virtual machine environment. Open the Contoso Data Editor app and complete the VM inventory details for VM2 and VM3.

Thanks,
<br>
Project Management Team

<br>


**Subject: Configure storage56050843**
---
Hello,

Our developers are testing a new Al application that will access data in a blob storage account. The developers need one of the storage account access keys to be rotated and they also need a new shared access signature (SAS) for one of the containers.

This is your task:

You need to perform the following tasks for the storage56050843 storage account:
* Rotate the key1 access key for the storage56050843 storage account.
* Open the Contoso Data Editor app and complete the Storage Account Key details for key2.
* For the images container in storage56050843, generate a shared access signature (SAS) for Read and List access only. Open the Contoso Data Editor app and complete the Blob SAS URL details.

Thanks,
<br>
Project Management Team

<br>


**Subject: Configure share1**
---
Hello,

The developers have a file share in the storage56050843 storage account that they plan to use to store debugging tools for the virtual machines. We need you to modify a few file share settings and upload some content to the file share.

This is your task:

You need to modify the following for the sharel file share in storage56050843:
* Set soft delete to 15 days.
* Change the access tier to Hot.

After you have made the configurations, upload the C:\Documentation\customers.csv file to the file share.

Thanks,
<br>
Project Management Team

<br>


**Subject: New app deployment**
---
Hello,

Our developers are preparing to deploy several new apps to Azure that will use Azure Al Search. We need you to prepare the environment and provide the developers with the information that they need to complete the deployments.

This is your task:

Open the Contoso Data Editor app and document the following details for the Azure subscription:
* Subscription ID
* Subscription name

Open the Contoso Data Editor app and document the state of the following resource providers from the Azure subscription:
* Microsoft.Billing
* Microsoft.Features
* Microsoft.Devices

For the RG3lod56050843 resource group, ensure that the following tags are set:
* Department: RD
* Customer: Fabrikam
* Environment: Production

Ensure that all Azure Al Search resources in the subscription have a tag of Department: Al

Thanks,
<br>
Project Management Team

<br>



**Subject: Prevent deletion**
---
Hello,

Our developers will be deploying resources to the RG3lod56050843 resource group by using scripting. We want to prevent the accidental deletion of resources in RG3lod56050843.

This is your task:

You need add a lock for RG3lod56050843 to prevent the accidental deletion of the resources that the developers deploy.

Thanks,
<br>
Project Management Team

<br>



**Subject: Status - Complete**
---
Thank you for helping the application developers by performing basic management tasks for storage accounts, virtual machines, and virtual networks in Azure.

We look forward to working with you again.

Regards,
<br>
Chief Technology Officer (CTO)
