# Basic commands

1. __Get out from the command__ - Ctrl+C

2. __Cls__ - clear

3. __Show Databases__ - show dbs

4. __Go inside any Database__ - use `databaseName`

5. __Create a new Database__ - use `databaseName`

6. __Create a new Collection__ - db.createCollection("`collectionName`")        //  _Responce will be {"Ok" : 1}, which means collection is created_

7. __Create a Data inside a Collection__ - db.`collectionName`.insertOne({`Data`})          // _Eg -db.`collectionName`.insertOne({name: "Mouse", brand: "Loitec"})_

8. __Create a Data inside a Collection__ - db.`collectionName`.insertOne({`Data`})          // _Eg -db.`collectionName`.insertOne({name: "Mouse", brand: "Loitec"})_

9. __Show the Data inside the Collection__ - db.`collectionName`.find()

10. __Delete a Database__ - db.drop`databaseName`       // _Be in the database you want to delete_

11. __Check the current Database__ - db

12. __Arrange data in Sequence__ - db.`collectionName`.find().pretty()

13. __Read__ - db.`collectionName`.find({"filter"})        // db.users.find({org: "abc"})

14. __Update a feild in each data__ - db.`collectionName`.updateOne({"filter"}, {"update_thing"})        // db.`user`.updateMany({ore: "abc"}, {$set: {city: "Bangalore"}})

15. __Add a new feild in some or a specific data__ - db.`collectionName`.updateMany({}, {$set: {filedKey: feildData}})        // db.`user`.updateMany({}, {$set: {city: "Bangalore"}})

16. __Add a new feild in each data__ - db.`collectionName`.updateMany({}, {$set: {filedKey: feildData}})        // db.`user`.updateMany({}, {$set: {city: "Bangalore"}})

17. __Delete One Data__ - db.`collectionName`.deleteOne({"filter"})        // db.users.deleteOne({org: "abc"})

