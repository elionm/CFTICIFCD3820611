# Module 02: Implement Azure functions



# Lab 02: Implement task processing logic by using Azure Functions



### Exercise 1: Create Azure resources

Created the Azure Storage account:

![02-01](images/02-01.png)

The the Connection string values:

![02-02](images/02-02.png)

Created the Function app:

![02-03](images/02-03.png)

### Exercise 2: Configure a local Azure Functions project

Create a new local Azure Functions project in the current directory :

![02-04](images/02-04.png)

Configure connection string in the local.settings.json file:

![02-05](images/02-05.png)

Build the .NET Core 3.1 project:

![02-06](images/02-06.png)

### Exercise 3: Create a function that’s triggered by an HTTP request

Create the function Echo using the HTTP trigger template:

![02-07](images/02-07.png)

Customize the function Echo:

![02-08](images/02-08.png)

Run the function app project:

![02-09](images/02-09.png)

Test the Echo HTTP-triggered function by using httprepl:

![02-10](images/02-10.png)

### Exercise 4: Create a function that triggers on a schedule

Create a new function using the **Timer trigger** template:

![02-11](images/02-11.png)

![02-12](images/02-12.png)

Running the function app (the function renders a simple message to the log every five minutes):

![02-13](images/02-13.png)

Modified the function to change the schedule to execute once every 30 seconds:

![02-14](images/02-14.png)

![02-15](images/02-15.png)

### Exercise 5: Create a function that integrates with other services

Add a new  Container to the storage account:

![02-16](images/02-16.png)

Upload the **settings.json** file to the just created container:

 ![02-17](images/02-17.png)

![02-18](images/02-18.png)

Create a new function named GetSettingInfo using the HTTP trigger template:

![02-19](images/02-19.png)

Modify the function to return the content of the **settings.json**  file uploaded:

![02-20](images/02-20.png)

Test the function by using httprepl:

![02-21](images/02-21.png)

### Exercise 6: Deploy a local function project to an Azure Functions app

Publishing the function app project:

![02-22](images/02-22.png)

Validating deployment:

![02-23](images/02-23.png)

![02-24](images/02-24.png)



### Exercise 7: Clean up your subscription

Deleted the resource group from Azure Cloud Shell:

![02-25](images/02-25.png)

