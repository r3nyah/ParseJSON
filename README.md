## Rest-API
API stands for Application Programming Interface, which is a piece of software that allows developers to integrate and allow two different applications to simultaneously connect to each other.
The purpose of using the API is to share data between these different applications, and also to speed up the application development process by providing a separate function so that developers no longer need to create similar features.
<br>
The REST API is one of the architectural designs contained within the API itself. And the way the RESTful API works is that the REST client will access data/resources on the REST server where each resource is. Or the data/resource will be distinguished by a global ID or URIs (Universal Resource Identifiers).
So, later the data provided by the REST server can be in the form of text, JSON or XML format. And currently the most popular and most widely used format is the JSON format.
## The HTTP methods commonly used in REST api are:
- [x] GET, serves to read data/resources from the REST server
- [x] POST, serves to create a new data/resource on the REST server
- [x] PUT, serves to update data/resources on the REST server
- [x] DELETE, serves to delete data/resources from the REST serve
- [x] OPTIONS, serves to get supported operations on resources from the REST server.
## Retrofit
Retrofit is an android library that helps developers to make requests to a REST API endpoint. 
This library was developed by Square Inc. (https://github.com/square) a company based in the United States. 
This library simplifies the program code used to access the REST API. Not only to access the REST API with a simple process 
(GET, POST, PUT, DELETE) retrofit also supports various authentication formats via http, adds headers to requests, 
adds parameters and sends data in the form of images to the server.
<br>
To access the REST api with Android's built-in code, a programmer has to create multiple workers and threads using Async Tasks.
This is not a simple process, especially if the request to the API requires security, special parameters to be added or even sending data other than sample
text in the form of images to the server. If you use Async Task, it is certain that programmers will have difficulty in making programs. It would be better
if all processes related to networking were handled by Retrofit. we will try to fetch data from http://www.omdbapi.com/?s=batman&apikey=2268147d.
