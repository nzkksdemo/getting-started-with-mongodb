## Getting Started with MongoDB

### Start mongodb server
start_mongo

## Connect to mongodb server
mongosh -u root -p XXXXXXXXXXXXXXXXX --authenticationDatabase admin local

### List databases
show dbs

### Create a database named training
use training

### Create a collection named mycollection in the database training
db.createCollection("mycollection")

### List collections
show collections

### Insert documents into a collection
db.mycollection.insertOne({"color":"white","example":"milk"})

### Count the number of documents in a collection
db.myCollection.countDocuments()

### List all documents in a collection
db.mycollection.find()
    
### Disconnect from mongodb server
exit
