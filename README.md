# ZRAP_TRAVEL_2143
## RAPM Learning from OpenSAP

1. **CDS Development**
	- Database ==> Interface View ==> Consumption View ==> Service Definition ==> Service Binding (Publish)

2. **Add Dummy Data**
	- Class - To Load the data to database or handle the logics of the program

3. **Authorization**
	- Create Data Element ==> Authorization Field ==> Authorization Object
	- Maintain the condition in the Auth Interface Object and inherit it in Auth Consumption Object

4. **CRUD Operations**
	- **Enable Behavior**
		- Create Behavior definition for Interface and maintain mapping ==> Create Behavior definition for Composition View. Save & Active. 
		- Now we can see Create/Edit/Deletion Actions in List and Object Page

	- **Perform Operations**
		- Implement the class in the Interface View
		- Make the necessary fields ready, managed, mandatory according to their functionality
		- Add Messages if required
		- Generate Behavior Implementation for the entity from the interface View
		- Add the functionality for each required method under Local Types of the class
		- Handle Missing Authorization methods from Interface View
		- Add required logics for authorization using Auth Objects and fields which we created earlier

	- **Draft Implementation**
		- Add *with draft* in the Interface View
		- Add *draft table table_name* in the Interface View and create the table for that entity
		- Add with draft  for all the associations implemented entity wherever required.

