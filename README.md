"# Basic-CRUD-App" 
CRUD is an acronym for the four basic types of SQL commands: Create , Read , Update , Delete . Most applications have some kind of CRUD functionality, and we can assume that every programmer had to deal with CRUD at some point. A CRUD application is one that uses forms to get data into and out of a database.


1) Create

Route: POST /classes

Effect on Database: Adds the class provided in the request body to the database

Response Body: { "class": The Newly-Created Class }

Success Response Code: 201



2) Read (All Classes)

Route: GET /classes

Effect on Database: None

Response Body: { "classes": [ Array of All Saved Classess ] }

Success Response Code: 200



3) Read (One Class)

Route: GET /classes/:id

Effect on Database: None

Response Body: { "class": The class with the specified ID }

Success Response Code: 200



4) Update
Route: PUT /classes/:id

Effect on Database: Updates the class with the specified ID to have the class information provided in the request body

Response Body: { "class": The updated class now saved in the database }

Success Response Code: 200



5) Delete

Route: DELETE /classes/:id

Effect on Database: Removes the class with the specified ID from the database

Response Body: None

Success Response Code: 204


As you get more practice with designing storage systems, incorporating CRUD operations into your models will become easier and easier.

