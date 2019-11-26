# ContactManagement
ContactManagement Application with CRUD operations

The solution Contact management is build using latest dotnet technology namely .net core 3.0.0 web application, Entity framework core 3.0.0 for data persistence and 
business functionality is exposed using dotnet WEB API. UI uses JQuery, bootstrap for styling.  Please open the project with visual studio 2019 and run the solution.

The Solution contains three projects :
1. ContactManagement : It's dotnet core web application and contains Razor pages for performing CRUD operations on Contact information.
2. ContactManagement.Core : This is dotnet core class library for storing core entities nad business clases of the Contact management application.
3.ContactManagement.data : This is Data access layer and contains clases for interacting with SQL DB and uses entity framework ORM

On executing the solution in Visual studio 2019 Welcome, Home, Contact management , About and Contact Us tabs.On clicking the Contact management tab, list of existing contacts is populated.
Existing contacts can be viewed, Edited and deleted using the Details, Edit and delete buttons provided at the end of each contact.New cotact can be added using Add button at the end of 
the cotact list. Existing contact can also be searched using the search option by providing full or partial name . This is case sensitive search option.

Contact Management business functionality is also exposed By Web API 
and can be accessed using API in the browser eg. https://localhost:44310/api/Contacts    https://localhost:44310/api/Contacts/3 , etc to get output in JSON format.



Instructions on how to open and Run Solution

1. Open https://github.com/PathakRitvij/ContactManagement

2.click on clone or download btton
3. Click on Download zip
4. ContactManagement-master.Zip file will be downloaded
5. Right click on and click Extract All option 
6. A folder named ContactManagement-master will be generated at the designated path
7. Right click on ContactManagement-master folder , select prperties and uncheck read only attribute for folder and all subfolders and files
8. Go to  ContactManagement-master inside ContactManagement-master i.e. to path like D:\ContactManagement-master\ContactManagement-master
9. Right click ContactManagement.Zip to extract the source code.
10. Right click on ContactManagement folder , select prperties and uncheck read only attribute for folder and all subfolders and files
11. open the path like D:\ContactManagement-master\ContactManagement-master\ContactManagement\ContactManagement\ContactManagement 
to find ContactManagement.sln file.
12. Right click on ContactManagement.sln and open with Visual studio 2019.
13. Run the solution.
14. Go to Contact Management tab to perform CRUD operations on contacts data.
