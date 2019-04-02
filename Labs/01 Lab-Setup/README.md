# Sign-into Portal

Sign in to https://portal.azure.com

# Create Resource Group 

Create Resource Group **AutoML-RG**

# Create Azure Machine Learning Workspace

To create workspace, follow step: https://docs.microsoft.com/en-us/azure/machine-learning/service/how-to-manage-workspace

# Create Azure Storage Account

To create a general-purpose v2 storage account in the Azure portal, follow these steps:
1. In the Azure portal, select All services. In the list of resources, type Storage Accounts. As you begin typing, the list filters based on your input. Select Storage Accounts.
2. On the Storage Accounts window that appears, choose Add.
3. Select the subscription in which to create the storage account.
4. Under the Resource group field, select Create new. Enter a name for your new resource group, as shown in the following image.
!['Blob Image]("https://github.com/Jscholtes128/Azure-Automated-ML-Workshop/blob/master/Media/Images/create-resource-group.png")

5. Next, enter a name for your storage account. The name you choose must be unique across Azure. The name also must be between 3 and 24 characters in length, and can include numbers and lowercase letters only.
6. Select a location for your storage account, or use the default location.
7. Leave these fields set to their default values: 
	|Field|Value|
	|Deployment model|Resource Manager|
	|Performance|Standard|
	|Account kind|StorageV2 (general-purpose v2)|
	|Replication|Locally redundant storage (LRS)|
	|Access tier|Hot|
8. Select Review + Create to review your storage account settings and create the account.
9. Select Create.
For more information about types of storage accounts and other storage account settings, see Azure storage account overview. For more information on resource groups, see Azure Resource Manager overview.
