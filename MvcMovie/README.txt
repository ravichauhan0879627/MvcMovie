Date system: 2025-05-06 1120 // ISO 8601
 used Visual Studio to create a new.NET 8.0.45 MVC project.


 1145 Confirmed that the project is developing successfully.

 10:45
 used the scaffolding tool in Visual Studio to add a new HelloWorldController.
 put into practice two fundamental action methods:
 By default, Index() produces a plain string.
 Welcome(): gives back a greeting.

 1114 Using the standard MVC route pattern, routing was confirmed.

 1140
 It functions properly when tested with a parameter-based URL.

 1216
 I changed the Index method in HelloWorldController before creating a new Razor view.
 Next, a new folder called HelloWorld was created in Views.
 Then, inside the HelloWorld foolder, a new razor view was created and given the default name Index.

 12:30
 After building the solution and testing the new index page, everything is operating as it should. 
 1320
 Add two dynamic parameters to the Welcome() method, bind the values in the new View Welcome, and assign the parameters here.

 1335
 Dynamic parameters were tested, and the list result was obtained.
 What comes next when the log is added and the data is exported?     binding of the model

 2025-05-20 0920
 added the "Movie" data model.  To improve formatting, Datatype and Display were added.  To modify the view's label, use the Display(Name = "Release Date") property.

 0950
 Utilize  Create a CRUD action using the scaffolding tool.
 Entity Framework Core-ready for database integration.  Make a migration and make updates.
 20250520140032_FirstCreation 

 1010.
 The CRUD operation was successfully tested on localhost.
20250520140506_InitialCreate.cs

23-05-24
1510
Added new a SeedData class is created to populate the database with initial data. This is invoked during application startup to ensure the database contains sample entries.

1540
test the chnages in browser and working fine.

1605
Use Display name and display type  to improve model display, format dates, and control database precision.

1615
tested and working.

1635 
20250527140811_Rating Migration added