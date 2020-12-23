https://loizenai.com/angular-node-js-postgresql-crud-example/

# Angular Node.js PostgreSQL Crud Example

![Angular Node.js PostgreSQL Crud Example](https://loizenai.com/wp-content/uploads/2020/12/Angular-Nodejs-Crud-Postgresql-Example.png)

Tutorial: “Angular Node.js PostgreSQL Crud Example – using Express and Sequelize ORM”

In the tutorial, I introduce how to build an Angular Node.js PostgreSQL CRUD Example RestAPIs Fullstack Project with the help of Express Web Framework and Sequelize ORM for POST/GET/PUT/DELETE requests with step by step coding examples.

## Architecture for Angular Node.js PostgreSQL CRUD Example Fullstack

![Fullstack Angular Nodejs CRUD Application – Overview Architecture](https://loizenai.com/wp-content/uploads/2020/07/Fullstack-Angular-Nodejs-CRUD-Application-Overview-Architecture.png)

- We build backend Nodejs Application that provides RestAPIs for POST/GET/PUT/DELETE Customer entities and store them in PostgreSQL/PostgreSQL database.
- We implement Angular Application that use Angular HTTPClient to interact (call/receive requests) with SpringBoot backend and display corresponding page view in browser.

## Nodejs CRUD RestAPIs Design

In the tutorial “Angular Node.js PostgreSQL Crud Example”, we create a Nodejs CRUD RestAPI with below diagram design:

![Nodejs-Build-CRUD-Application-Architecture-Overview](https://loizenai.com/wp-content/uploads/2020/07/Nodejs-Build-CRUD-Application-Architecture-Overview.png)

We have 4 main blocks for backend Node.js application:

- For building RestAPIs in Node.js application, we use Express framework.
- For interacting with database PostgreSQL/PostgreSQL, we use Sequelize ORM.
- We define APIs URL in router.js file
- We implement how to process each API URL in controller.js file
- We use Bootstrap and JQuery Ajax to implement frontend client.

![Backend Nodejs Build CRUD Application – Project Structure](https://loizenai.com/wp-content/uploads/2020/07/Backend-Nodejs-Build-CRUD-Application-Project-Structure.png)

- config package is used to configure Sequelize and PostgreSQL/PostgreSQL database environment
- models package is used to define a Sequelize model to interact with database
- routers package is used to define Rest APIs’ URL
- controllers is used to implement business logic to processing each RestAPIs
- views folder is used to implement HTML view pages
- resources/js folder is used to implement JQuery Ajax to Post/Get/Put/Delete RestAPIs

## Angular CRUD Design – Angular Node.js PostgreSQL Crud Example

Now I explain more about architecture of Angular application in the tutorial “Angular Express PostgreSQL CRUD Example”:

![Angular Nodejs CRUD Application – Frontend Design Architecture](https://loizenai.com/wp-content/uploads/2020/07/Angular-Nodejs-CRUD-Application-Frontend-Design-Architecture.png)

Angular CRUD Application is designed with 3 main layers:

- Service Layer is used to define Angular Common Services and HttpClient Services to interact with RestAPIs
- Component Layer is used to define Angular Components to show views in Browser for interacting with Users
- Router Layer is used to route URLs mapping with the corresponding Angular Components

Angular Project Structure in the tutorial: “Angular Node.js PostgreSQL Crud Example”

![Angular Nodejs CRUD Application – Project Structure](https://loizenai.com/wp-content/uploads/2020/07/Angular-Nodejs-CRUD-Application-Project-Structure.png)

Angular CRUD Application defines 3 components, 2 services, 1 routers, and 2 data models:

– Components:

- add-customer component is used to add a new customer to system
- list-customer component is used to show all customers on view pages, delete a customer and update a customer
- message component is used to define a view to show logging message on browser

– Services:

- customer.service.ts defines POST/GET/PUT/DELETE HTTP requests to SpringBoot RestAPIs with the built-in Angular HttpClient.
- message.service.ts defines an array storage to log all messages when Angular CRUD App running

– Router: app-routing.module.ts defines how to map a corresponding Angular component with an URL.

– Models:

customer.ts defines the main data model of our application.
message.ts defines the response data model between SpringBoot and Angular application.

## Project Goal – Angular Node.js PostgreSQL Crud Example
Here is the overview project goal of the tutorial “Angular Express PostgreSQL CRUD Example”:

– Add new Customer:

![Angular Nodejs CRUD App – Add New Customers](https://loizenai.com/wp-content/uploads/2020/07/Angular-Nodejs-CRUD-App-Add-New-Customers.png)

– List All Customers:

![Angular Nodejs CRUD Application – List All Customers](https://loizenai.com/wp-content/uploads/2020/07/Angular-Nodejs-CRUD-Application-List-All-Customers.png)

– Details a Customer:

![Angular Nodejs CRUD App – Details a Customer](https://loizenai.com/wp-content/uploads/2020/07/Angular-Nodejs-CRUD-App-Details-a-Customer.png)

– Update a Customer:

![Angular Nodejs CRUD Application – Update a Customer](https://loizenai.com/wp-content/uploads/2020/07/Angular-Nodejs-CRUD-Application-Update-a-Customer.png)

– Delete a Customer:

![Angular Nodejs CRUD App – Delete a Customer successfully](https://loizenai.com/wp-content/uploads/2020/07/Angular-Nodejs-CRUD-App-Delete-a-Customer-successfully.png)

– Check database records:

![Angular Nodejs CRUD App – Check Database Records](https://loizenai.com/wp-content/uploads/2020/07/Angular-Nodejs-CRUD-App-Check-Database-Records.png)

## Video Guide – Angular Node.js PostgreSQL Crud Example

https://youtu.be/vytbP5vdh2U

## Related posts

- [Angular 10 Nodejs PostgreSQL CRUD Example](https://loizenai.com/angular-10-nodejs-postgresql-crud-example-using-express-restapis-sequelize-tutorial/)
- [Angular 8 Nodejs PostgreSQL CRUD Example](https://loizenai.com/angular-8-nodejs-postgresql-crud-example/)
- [Angular 9 Node.js PostgreSQL CRUD Example](https://loizenai.com/angular-9-node-js-postgresql-crud-example/)
- [Angular Node.js Mysql Crud Example](https://loizenai.com/angular-11-node-js-mysql-crud-example/)
- [Angular Node.js Mysql Crud Example](https://loizenai.com/angular-node-js-mysql-crud-example/)
- [Angular 11 Node.js PostgreSQL Crud Example](https://loizenai.com/angular-11-node-js-postgresql-crud-example/)
