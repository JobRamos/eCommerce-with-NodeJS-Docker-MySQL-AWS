##Installation
* Install dependencies in `package.json`: `npm install`

##Usage
* Import Database/astore.sql in a MySQL instance (RDS or locally)
* Modify config/database.js to add your MySQL credentials for connectivity
* Execute `node bin/www.js` or 'node start' from project directory
* Once the project is correctly running it can be containerized with Docker by using the following commands:
# docker build -t e-commerce .
# docker run -it -p 3000:3000 e-commerce

After the Docker image has been created it can be send and deployed anywhere else (EKS, ECS, locally, etc).


