# Angular-assignment

The assignment consists in creating a simple angular app that displays a table of users.

Steps to start developing:
1. Checkout this repository
2. Run `npm install`
3. Run `npm start`
4. Go to http://localhost:4200

Requirements:
1. Create a branch (with any name) from this repository
2. Create the user's table
	* The table must be in its own module and component
	* The columns for the table should be:
		* Name (field `name`)
		* Company (field `company.name`)
		* Address (which contains fields `street`, and `city` together)
	* Maximum rows per page should be 5
	* The table must have pagination
	* You must do an HTTP call to get the data from: https://jsonplaceholder.typicode.com/users
3. All functionalities must be covered with unit tests
4. Make it look pretty is optional (feel free to use whatever component library / styling framework you like)