# mongoDB-with-python

prerequisite.
1. download and instal mongodb in your remote computer.
2. download mongDB compass(A GUI) to see all the existing database

MongoDB follows No-Sql dbms.
Data stored in form of collection in JSON like Document.

For Example:

{         
	user:'user1',         
	message: 'My first comment',         
	dateCreated: new Date(2011,1,20,2,15),         
	like: 0 

}

check version of mongoDB by the command.

mongod --version

Before adding any data in databse make sure to start your surver.
By running the command.

"C:\Program Files\MongoDB\Server\4.2\bin\mongo.exe"

replace 4.2 with the version you have downloaded.

STEPS FOR ADDING DATA 

1. First of all load the data in the program. 
2. The data can be loaded using pandas or numpy module. 
3. Bring out the predefine functions in order to load the data in the correct form. 
4. If the data contain any null or nan field value then the value needs to be converted into the integer 0 value. 
5. 0 integer value will be treated as the nan values. 
6. Common examples of NoSQL database is mongodb database. 
7. Mongodb is the most famous NoSQL database. 
8. In order to add the data we need to convert the data into the list of dictinoary which contains all the field values and data coresponding to that values. 
9. Using insert_many() function all the values can be added into the server of the mongodb database
