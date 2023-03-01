# Storage Account & Firewall
## This project will be about generating an Azure Storage account and implementing a Firewall in it as well as integrated VM via file share..

1) Provision the lab environment:

-Create an Azure subscription if you haven't already.
-Create a resource group to contain all the resources for this lab.
![Alt text](https://github.com/Alijon1992/Create-storage-sccount-firewall-and-link-it-to-VM/blob/main/1-creating%20resource%20group.png)

-Create a virtual network with a subnet for the storage account and VM.
-Create a VM in the virtual network.
-Create and configure Azure Storage accounts:

2) Go to the Azure portal and navigate to Storage accounts.

-Click the +Add button to create a new storage account.
-Enter a unique name for the storage account and select the subscription and resource group you created in step 1.
-Select the desired location and performance tier for the storage account.
-Leave the advanced options as their defaults and click the Review + Create button.
-Review the settings and click the Create button to create the storage account.

3) Manage blob storage:

-Navigate to the newly created storage account in the Azure portal.
-Click on the Blobs service in the left-hand menu to manage blob storage.
-Upload files or create new containers to store blobs.
-Set permissions and access policies for blob containers and blobs.

4) Manage authentication and authorization for Azure Storage:

-Navigate to the Access keys section of the storage account in the Azure portal.
-Retrieve the storage account's connection string and access keys.
-Use these credentials to authenticate and authorize access to the storage account from your applications or services.

5)Create and configure an Azure Files share:

-Navigate to the Files service in the left-hand menu of the storage account in the Azure portal.
-Click the +File share button to create a new file share.
-Enter a unique name for the file share and configure the desired properties, such as quota and share level access policies.
-Click the Create button to create the file share.

6) Manage network access for Azure Storage:

-Navigate to the Networking section of the storage account in the Azure portal.
-Configure the firewall and virtual network settings to control access to the storage account.
-Add firewall rules to allow access from specific IP addresses or ranges.
-Configure virtual network rules to allow access from specific virtual networks or subnets.
-Integrate the VM created in step 1 with the file share created in step 5 by mounting the file share as a network drive on the VM.

***That's it! You've now created and configured an Azure Storage account with a Firewall and integrated a VM via file share.




