# DeliVeggie
ASP.net core web application to list products and product details


Steps required to build & run the application
----------------------------------------------

1. Download the zip file namely "DeliVeggie.zip" from below GitHub location 
	https://github.com/ssbarun/DeliVeggie

2. Extract the solution from "DeliVeggie.zip" file & open the solution file using Visual Studio.

3. Build the application, in case of any warnings or errors, please rebuild all projects separately.

4. Please update connection string in appSettings.json file in Web project to point to the required database.

5. For creating required database tables, please run the migration from the Nuget Package Manager console from the Tools Menu in Visual Studio
	a. Please select the DAL project as the default project in the Package Manager console. 
	b. In the shell command, please execute "update-database" to create the required database & tables.

6. Please execute "InsertData" file from the query window to insert data in master table from Microsoft Sql Server Management Studio after connecting to the database and selecting the required database name.
