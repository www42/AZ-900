**Subject: General guidelines**
---
Hello,

Some resources in this scenario might take several minutes to deploy. Please review the other tasks in the lab while the deployment completes. You may perform other tasks that do not rely on that deployment.

Thank you for agreeing to help our team deploy and configure Azure Monitor.

We have some general guidelines that you must follow when you perform tasks in Azure.
* When creating objects, use the default settings, unless there are requirements that require different configurations.
* Only create, delete, or modify objects to achieve the stated requirements. Unnecessary changes to the environment can adversely affect your final score.
* If there are multiple approaches to achieving a goal, always choose the approach that requires the least amount of administrative effort.

Thanks,
<br>
Chief Technology Officer (CTO)

<br>


**Subject: Existing environment**
---
Hello,

Here are your credentials for accessing our resources in Azure:

User name:
<br>
Password:

You can also find the sign in information in the **Instructions** tab.

You have been given rights to the RG1 resource group. Please create all Azure objects in this resource group.

We have deployed the following Azure resources:
* A virtual network named **VNET1** that contains one subnet
* A virtual machine named **VM1** that hosts a web app named **VM1-app**, and
* An Azure App Services web app named **AzureWebApp1-36932723**

Thanks,
<br>
Network administrator

<br>


**Subject: Deploy Log Analytics**
---
Hello,

We have recently started using Azure to host various web apps. We now want to implement a centralized strategy for monitoring and alerting by using Azure Monitor.

This is your task:

You need to create and configure a Log Analytics workspace named **LogAnalytics1** that meets the following requirements:
* Data must be retained for **60 days**.
* Ensures that the **36932723-AppLogExaminers** group has read access to all the logs in **LogAnalytics1**.
* Ensures that the maximum amount of data collected per day does NOT exceed **200 GB**.

Thanks,
<br>
Project Management Team

<br>


**Subject: Monitor Web Apps**
---
Hello,

Once you complete the deployment of **LogAnalytics1**, we want to start monitoring **AzureWebApp1-36932723**. The web app is a **NET core app**.

This is your task:

You need to configure logging for **AzureWebApp1-36932723** to meet the following requirements:
* Collect monitoring data by using Application Insights. The data must be logged to **LogAnalytics1**.
* Ensure that logging for the NET core Snapshot Debugger is disabled.
* Enable file and configuration change tracking for **AzureWebApp1-36932723**.
* Ensure that the HTTP logs for **AzureWebApp1-36932723** are sent to **LogAnalytics1**.
* Ensure that the SQL Insights data for the Azure SQL database used by the web app is sent to **LogAnalytics1**.

Thanks,
<br>
Project Management Team

<br>


**Subject: Configure monitoring for Compute services**
---
Hello,

Once you complete the deployment of **LogAnalytics1**, we want to start monitoring compute services.

This is your task:

You need to collect telemetry data from **VM1** by using the Azure Monitor Agent and log the data to **LogAnalytics1**. The solution must meet the following requirements:
* Create a data collection rule (DCR) that logs the following data:
	* IIS logs,
	* Audit failure events from the Security event log,
	* Critical and error events from the System event log, and
	* Critical and error events from the Application event log.
* Enable VM insights.

You also need to monitor HTTP availability to the public IP address of **VM1** from the public IP address of **Linux-VM**. The data must be logged to **LogAnalytics1**.

Thanks,
<br>
Project Management Team

<br>


**Subject: Configure Alerts**
---
Hello,

We want you to configure email alerts for abnormal conditions, such as high CPU load.

This is your task:

You need to configure alerting to meet the following requirements:
* Create an action group named **AG1** that sends notifications to **alerts@contoso.com**.
* Create an alert rule that monitors when the average percentage CPU of **Linux-VM** exceeds 80. When the alert is triggered, it must send an email to **alerts@contoso.com**.

Thanks,
<br>
Proiect Management Team

<br>


**Subject: Status - Complete**
---
Thank you for helping our team deploy and configure monitoring for our Azure infrastructure.

We look forward to working with you again.

Regards,
<br>
Chief Technology Officer (CTO)

