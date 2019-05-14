# Bob's Burger's - Burger of the Day App
This app uses MySQL, Node, Express, Handlebars, and a homemade ORM.
Following the MVC design pattern this app uses Node and MySQL to query and route data, and Handlebars to generate the HTML.

### Tech Used:
* Model-View-Controller (MVC)
* Object Relational Mapping (ORM)
* Express.js
    * HTTP Requests (GET, POST)
    * Routes and static content
    * Body Parser
    * Handlebars engine integration
* Node.js
    * Backend API calls
* Handlebars Templates and Layouts
* MySQL / JawsDB

## [View Site](https://hidden-cliffs-31813.herokuapp.com/)


![Eat-Da-Burger Screenshot](public/assets/img/bobs-screenshot.png?raw=true "Eat-Da-Burger")


### Prerequisites
1. Node.js - Eat-Da-Burger requires Node to be installed

2. To install node visit [Node.js Website](https://nodejs.org/en/ "Node.js") and install node for your operating system.


### Installation
1. Clone the Git repository

   ```
   $ git clone <repo>
   ```
2. Navigate to the directory and install the dependencies 
   ```
   $ npm install
   ```


### Using the Application Locally
1. Create a MySQL database and run the following files to set up the schema
    * db/schema.sql
    * db/seeds.sql
2. Configure the database connection settings in config/connection.js
3. Navigate to the repository folder and run server.js to start

   ```
   $ node server.js
   ```

4. Navigate to localhost:8080 in the browser

5. Add burgers to the New Burgers List and eat them!

![Eat-Da-Burger Screenshot](public/assets/img/Gene_Belcher.png?raw=true "Eat-Da-Burger")



   
