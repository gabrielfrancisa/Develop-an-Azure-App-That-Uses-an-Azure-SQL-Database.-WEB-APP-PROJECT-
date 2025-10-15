# Develop-an-Azure-App-That-Uses-an-Azure-SQL-Database.-WEB-APP-PROJECT-
This project, I create and deploy an Azure mobile app by using a Visual Studio.


## At the end of the Project we will create the following:
1.	Created an Azure SQL Database.
2.	Created an Azure web app by using an App Service.
3.	Deployed an Azure web app.
4.	Tested connectivity to an Azure mobile client app.

## steps
1.	First, I create an Azure SQL Database to host the mobile app data, and then create the mobile app back end by using an App Service Web App that is connected to the Azure SQL Database. 
2.	Next, configure a development environment on an Azure, and then deploy the mobile app back end by using Visual Studio. 
3.	Finally, test the mobile app by using the Android emulator in Visual Studio.

## 2.Create an Azure SQL Database
>>> Open Microsoft Edge, sign in to the Azure portal 

>>> Select the Type Text icon to type the associated text into the current field in the virtual machine.

## Create an Azure SQL Database and a new logical SQL server by using the values in the following table. For any property that is not specified, use the default value.
>>> Property       ----------------------------	Value
1.	Resource group:	corp-datalod55543658
2.	Database name:	tododb
3.	Server name:	Create new: sv55543658
4.	Location:	(US) East US
5.	Authentication method:	Use SQL authentication
6.	Server admin login:	AzureAdmin
7.	Password:	AzPvvb******!
8.	Workload environment:	      Development
9.	Service tier:	Standard (Budget friendly)
10.	DTUs:	10
11.	Data max size (GB):	250
12.	Connectivity method:	Public endpoint
13.	Allow Azure services and resources to access this server: 	Yes
14.	Add current client IP address:	Yes


## 3.Create an Azure Web App
>>> Create an Azure Web App by using the values in the following table. For any property that is not specified, use the default value.

>>> Property    -----------------------	Value
1.	Resource Group:  *********88da55543658
2.	Name:	mammmnm8888
3.	Unique default hostname: 	Disabled
4.	Publish	Code
5.	Runtime stack:	ASP.NET V4.8
6.	Region:	East US
7.	Windows Plan: (East US)	AppPlan1
8.	Sku and size:	Standard S1

>>> Open a new Microsoft Edge browser tab, go to the URL for the new Web App at https:// *********88da55543658.azurewebsites.net, and then verify that the default home page is displayed.



## 4.Publish an Azure app by using Visual Studio
1.	Connect to Azure account if promted too, launch the Visual Studio.
2.	If prompted to allow your PC to be discoverable by other PCs and devices on this network, select No.
3.	Start Visual Studio 2022 by signing in to your Microsoft work or school account 4
4.	It will take approximately 2-3 minutes for Visual Studio to open for the first time. Do not try to open Visual Studio more than once, as this will open multiple instances, which will slow things down, and then you will have to close the other instances later to release the memory used.
5.	Wait for Visual Studio to initialize before continuing.


## Open Windows PowerShell, and then run the following commands to clone the GitHub repo that contains the Apache Cordova mobile app solution and verify the download:
>>> PowerShell:-
cd "c:\users\student\Documents\Visual Studio 2022"

>>> PowerShell:-
git clone https://github.com/Azure-Samples/dotnet-sqldb-tutorial.git

>>> PowerShell:-
cd ./dotnet-sqldb-tutorial/

>>Close Windows PowerShell.

## In Microsoft Visual Studio, open the DotNetAppSqlDb project in C:\Users\Student\Documents\Visual Studio 2022\dotnet-sqldb-tutorial\DotNetAppSqlDb.

>>Wait for the Project to be opened.

>>Publish the DotNetAppSqlDb project to the existing ma55543658 Azure App Service.

>>Configure the profile to ignore Application Insights, and then connect the publish profile to the tododb Azure SQL database using MyDBConnection as the connection string name.

>>Configure the database connection string to Server=tcp:sql55543658.database.windows.net,1433;Initial Catalog=tododb;Persist Security Info=False;User ID=SQLAdmin;Password=AzureSQLPassw0rd!;MultipleActiveResultSets=False;Encrypt=True;TrustServerCertificate=False;Connection Timeout=30;, and then publish the project.

>>Wait for the publish operation to complete. It will take approximately 2-3 minutes.

## When prompted, sign in as User
>>> On the Publish page, in Hosting, in Site, select the link and confirm that the tododb web page is displayed.

>>> If you receive an error that the application does not load, return to the Azure portal and ensure that the ma55543658 Azure App Service connection string named MyDbConnection is set to Server=tcp:sv55543658.database.windows.net,1433;Initial Catalog=tododb;Persist Security Info=False;User ID=AzureAdmin;Password=AzPwd55543658!;MultipleActiveResultSets=False;Encrypt=True;TrustServerCertificate=False;Connection Timeout=30; and SQLAzure as the type. If you still do not see the default web page, republish the app.


The end
Congratulations, 
