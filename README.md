E-Commerce Back End
User Story
md
Copy code
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
Acceptance Criteria
md
Copy code
GIVEN a functional Express.js API
WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
THEN I am able to connect to a database using Sequelize
WHEN I enter schema and seed commands
THEN a development database is created and is seeded with test data
WHEN I enter the command to invoke the application
THEN my server is started and the Sequelize models are synced to the MySQL database
WHEN I open API GET routes in Insomnia for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia
THEN I am able to successfully create, update, and delete data in my database
Getting Started
To start using this back end for your e-commerce website, follow these steps:

Clone the repository to your local machine.

Install dependencies by running npm install.

Create a .env file in the root directory of the project and add the following environment variables:

makefile
Copy code
DB_NAME=your_database_name
DB_USER=your_mysql_username
DB_PASSWORD=your_mysql_password
DB_HOST=localhost
DB_PORT=3306
Run the schema and seed commands to set up the database and seed it with test data:

arduino
Copy code
npm run schema
npm run seed
Once the database is set up, start the server by running npm start.

With the server running, you can use Insomnia or any other API testing tool to test the GET, POST, PUT, and DELETE routes for categories, products, and tags.

Dependencies
Express.js
Sequelize
MySQL2
dotenv
Contributing
Contributions are welcome! If you find any issues or have suggestions for improvements, please feel free to open an issue or submit a pull request.

License
This project is licensed under the MIT License - see the LICENSE file for details.

### Walkthrough Video
https://drive.google.com/file/d/1xTkRckg8bUYeVzfLpgJ_4ZDrl01lG-lB/view

