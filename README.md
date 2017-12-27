# mean4_sample
Mean stack applications with CRUD using Angular 4

For the CRUD operations,
Read is done by following the tutorial from URL: https://coursetro.com/posts/code/84/Setting-up-an-Angular-4-MEAN-Stack-(Tutorial)

CRUD to follow soon.

How to execute:
---------------
Start mongod in a terminal.
Run ng build in project folder.
Run node server is project folder.

server is the name of the JS file in which the ndoe/express commands are defined.

Routes are defined in api.js under routes folder
Data access service is defined in data.service in agular
connections to mongodb are defined in api.js which is the router file.

It is not recomonded to do that way but it is a quick and dirty hack.

In this project, both the angular, Node  and express applications co exist. 
It is a good approach to have angular (UI) components defined and running as a different project in its own node container and express and node running in a different node container.

There will be issues in inter process communication. This can be overcome with additional node modules.
It is called CORS