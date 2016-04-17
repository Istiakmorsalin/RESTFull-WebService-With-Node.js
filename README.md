# RESTFull-WebService-With-Node.js

Complete RESTFull WebService with Node.js

Implemented REST VERBS:
1.POST
2.GET
3.PATCH
4.PUT
5.DELETE 

Used Mongodb as a database and Mongoose to connect with it. 

API DOCUMENTATION:

1.localhost:portnumber/api/books [POST] {Create a Book} 
  
   Consumes a Requestbody application.json
   produce a Responsebody application.json

2.localhost:portnumber/api/books [GET] {GET all Books}

   Produce a Responsebody application.json

3.localhost:portnumber/api/books/bookId [GET] {GET a single Book}

   Produce a Responsebody application.json

4.localhost:portnumber/api/books/bookId [PUT] {Update  Book}

   Consumes a Requestbody application.json
   produce a Responsebody application.json

5.localhost:portnumber/api/books/bookId [PATCH] {UPDATE Partial Book} 

   Consumes a Requestbody application.json
   produce a Responsebody application.json

6.localhost:portnumber/api/books/bookId [DELETE] {DELETE A Book} 

   Produce a Responsebody application.json

