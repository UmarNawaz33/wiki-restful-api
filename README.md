<!-- ABOUT THE PROJECT -->
## About The Project
This is a simple restful api for articles. This restful api allows you to perform the CRUD operations on a database of articles.

<!-- GETTING STARTED -->
## Getting Started
To run this project first you need to setup your enviroment for nodejs. After that you need to:
* Clone this project.
* Use `npm install` command to install all the packages.

#### To Run Locally
* Setup and Configure mongb locally.
* Use `mongod` command to start mongodb server using terminal.
* Use `node app.js` command to start the node server on localhost.

#### To Run on Server
* Setup and Configure mongodb atlas for your project.
* Setup and Configure server(heroku) for your app.
* Update `.env` file accordingly.
* For Deployment, follow the guidelines provided by heroku or any other server you are using.

#### Testing

For testing the api you can use [Postman](https://www.postman.com/).

### Built With
This application is built with the following:
* [Node JS](https://nodejs.org/en/)
* [Express JS](https://expressjs.com/)
* [MongoDb](https://www.mongodb.com/)

<!-- API Endpoints -->
## API Endpoints
This api allows all CRUD operations and it has following endpoints:
* [GET] `http://localhost:3000/articles` GET request on this endpoint gives you all the articles in database.
* [POST] `http://localhost:3000/articles` [Request Body Parameters] `title, content` POST request on this endpoint allows you to add article to database.
* [DELETE] `http://localhost:3000/articles` Delete request on this endpoint deletes all the articles in database.
* [GET] `http://localhost:3000/articles/:articleTitle` [Request Parameter] `article title` GET request on this endpoint gives you the article with requested title.
* [PUT] `http://localhost:3000/articles/:articleTitle` [Request Body Parameters] `title, content` [Request Parameter] `article title` PUT request on this endpoint allows you to update article with specified title.
* [DELETE] `http://localhost:3000/articles/:articleTitle` [Request Parameter] `article title` DELETE request on this endpoint allows you to delete article with specified title.


<!-- LICENSE -->
## License

Distributed under the MIT License. See [LICENSE](https://github.com/UmarNawaz33/wiki-restful-api/blob/main/LICENSE) for more information.

<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements
* [body-parser](https://www.npmjs.com/package/body-parser)
* [express](https://www.npmjs.com/package/express)
* [mongoose](https://www.npmjs.com/package/mongoose)

