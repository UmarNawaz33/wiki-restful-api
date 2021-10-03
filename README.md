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
<table>
  <tr> <th>Reuest</th> <th>Path</th> <th>Body Parameters</th> <th>Request Parameters</th> <th>Explanation</th> </tr>
  <tr> <td><b>GET</b></td> <td>http://localhost:3000/articles</td> <td>-</td> <td>-</td> <td>to get all articles</td> </tr>
  <tr> <td><b>POST</b></td> <td>http://localhost:3000/articles</td> <td>title, content</td> <td>-</td> <td>add article in database</td> </tr>
  <tr> <td><b>DELETE</b></td> <td>http://localhost:3000/articles</td> <td>-</td> <td>-</td> <td>delete all articles</td> </tr>
  <tr> <td><b>GET</b></td> <td>http://localhost:3000/articles/:articleTitle</td> <td>-</td> <td>articleTitle</td> <td>get article with specific title</td> </tr>
  <tr> <td><b>PUT</b></td> <td>http://localhost:3000/articles/:articleTitle</td> <td>title, content</td> <td>articleTitle</td> <td>update article with specified title</td></tr>
  <tr> <td><b>DELETE</b></td> <td>http://localhost:3000/articles/:articleTitle</td> <td>-</td> <td>articleTitle</td> <td>delete article with specified title</td> </tr>
</table>

<!-- LICENSE -->
## License

Distributed under the MIT License. See [LICENSE](https://github.com/UmarNawaz33/wiki-restful-api/blob/main/LICENSE) for more information.

<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements
* [body-parser](https://www.npmjs.com/package/body-parser)
* [express](https://www.npmjs.com/package/express)
* [mongoose](https://www.npmjs.com/package/mongoose)

