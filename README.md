# E-commerce Back End 
This project is a interactive back end databse for an ecommerce store. The application uses 
MYSQL2 and Sequelize to connect to the database and the dotenv package to use environment variables to store sensitive data, like a user’s MySQL username, password, and database name. 

# Features
* The store has categories that can be viewed all at once or indiviually with get routes. You can also create new categories with a post route, update existing categories with a put route, or delete a category with a delete route.
* The products in the store have an id, name, price, stock count, tags, and belong to a category. The procuts can be viewed, created, updated, and deleted the same way the categories can.
* All of the products have tags that describe a product that can be interacted with in the same manner as the categories or products.

# Installation 
Once you clone the repostiory, install the required packages with npm install. Make a .env to store the database name, user, and password. Set up the database by starting up a mysql shell and running source db/schema.sql. Exit the mysql shell and enter npm run seed in the command line. Then enter npm start and the server will start up and you can start making requests!

# References
Link to repository: https://github.com/Jaron15/Ecommerce-back-end.git

Walkthrough video: https://watch.screencastify.com/v/KR6y1RVhGoD3rP9pVC8d
