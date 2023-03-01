# Storage Account & Firewall
## This project will be about generating an Azure Storage account and implementing a Firewall in it as well as integrated VM via file share..

1) Provision the lab environment:

-Create an Azure subscription if you haven't already.

-Create a resource group to contain all the resources for this lab.


<img width="745" alt="1-creating resource group" src="https://user-images.githubusercontent.com/121365233/222039407-2ca05772-98e7-4155-be74-1a97866e017b.png">


-Create a virtual network with a subnet for the storage account and VM.

<img width="424" alt="2-Creating Vnet   snet" src="https://user-images.githubusercontent.com/121365233/222032803-6bcc378a-8d89-4f68-b3f3-31a09e383b2e.png">

-Create a VM in the virtual network.

<img width="802" alt="3-creating VM inside specified Vnet, snet, and RG" src="https://user-images.githubusercontent.com/121365233/222032946-aa5c4a70-391d-48a4-815a-f254896b23fe.png">

2) Create and configure Azure Storage accounts:

-Create new resource group for storage account.

<img width="511" alt="4-creating second RG for Storage account" src="https://user-images.githubusercontent.com/121365233/222033048-bbf591e7-6650-4fcc-aa53-1860810206ad.png">

-Click the +Add button to create a new storage account.

***-Enter a unique name for the storage account and select the subscription and resource group you created in previously.
-Select the desired location and performance tier for the storage account.
-Leave the advanced options as their defaults and click the Review + Create button.
-Review the settings and click the Create button to create the storage account.

<img width="775" alt="5-creating storage account" src="https://user-images.githubusercontent.com/121365233/222033279-ff2c0e38-c070-4303-9c01-822f2284d471.png">

3) Manage blob storage:

-Navigate to the newly created storage account in the Azure portal.
-Click on the Blobs service in the left-hand menu to manage blob storage.
-Upload files or create new containers to store blobs.

<img width="1420" alt="6-creating containers" src="https://user-images.githubusercontent.com/121365233/222033520-b2bccf35-0a43-4267-a55b-63cb54e135de.png">

-Upload your files to created containers
--Note: Files can be uploaded from linked devices(VM or Local) whenever needed.

<img width="1433" alt="7-uploading file to container" src="https://user-images.githubusercontent.com/121365233/222033700-cf3a08be-b590-4a67-a8bd-b13e4424979b.png">

-Set permissions and access policies for blob containers and blobs.

4) Manage authentication and authorization for Azure Storage:

-Navigate to the Access keys section of the storage account in the Azure portal.
-Retrieve the storage account's connection string and access keys.
-Use these credentials to authenticate and authorize access to the storage account from your applications or services.

<img width="1426" alt="8-managing access to containers via token" src="https://user-images.githubusercontent.com/121365233/222036593-bc1e3c5a-21dc-484d-a359-b7795124d0a5.png">

5)Create and configure an Azure Files share:

-Navigate to the Files service in the left-hand menu of the storage account in the Azure portal.
-Click the +File share button to create a new file share.
-Enter a unique name for the file share and configure the desired properties, such as quota and share level access policies.
-Click the Create button to create the file share.

<img width="1419" alt="9-create configuring azure file share" src="https://user-images.githubusercontent.com/121365233/222036758-fb5e1c2b-34e6-4409-9a45-72f85e494d29.png">

6) Manage network access for Azure Storage:

-Navigate to the Networking section of the storage account in the Azure portal.

-Configure the firewall and virtual network settings to control access to the storage account.

<img width="1417" alt="11-configuring firewall and Vnet settings" src="https://user-images.githubusercontent.com/121365233/222037364-bf502050-f0c7-4fec-837f-7f20e9ec5d66.png">

-Add firewall rules to allow access from specific IP addresses or ranges.
-Configure virtual network rules to allow access from specific virtual networks or subnets.

<img width="715" alt="10-Enabling specific VM and subnet to connect " src="https://user-images.githubusercontent.com/121365233/222036947-ae9611b6-64be-482f-b480-02c4ce167c85.png">

-Integrate the VM created in step 1 with the file share created in step 5 by mounting the file share as a network drive on the VM. 

<img width="862" alt="13-Manage network access for Azure Storage" src="https://user-images.githubusercontent.com/121365233/222037797-d12e1df9-dfbf-45a6-89bb-2c5488c0df13.png">

<img width="1280" alt="Screenshot 2023-02-28 at 5 12 16 PM" src="https://user-images.githubusercontent.com/121365233/222037937-d1484a35-0f3c-4975-842b-913b10f6370f.png">


***Additional
-Add Multi-Factor Authentication for more secure access!

<img width="1112" alt="12-Setting up Multi-Factor Authentication" src="https://user-images.githubusercontent.com/121365233/222039222-542f3f03-81c9-446e-a1ce-644526e97499.png">

***That's it! You've now created and configured an Azure Storage account with a Firewall and integrated a VM via file share.




