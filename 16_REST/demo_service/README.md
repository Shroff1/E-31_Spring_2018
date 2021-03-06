# REST
This demo adds a REST Service to the example in the [demo](https://github.com/RobertFrenette/E-31_Spring_2018/tree/master/16_REST/demo) folder for this Section..

## Execute in Terminal
```
$ cd demo_service
$ npm install
  ...
$ npm start
```

## Test in Postman (HTTP Verb / CRUD Action)

### POST / Create
[http://localhost:3000/api/create](http://localhost:3000/api/create)

![Create](img/create.png?raw=true "Create")


### GET / Read
+ Replace MOUNTAIN_ID in URI below with _id returned in Create above

[http://localhost:3000/api/MOUNTAIN_ID](http://localhost:3000/api/MOUNTAIN_ID)

![Read](img/read.png?raw=true "Read")


### PUT / Update
+ Replace MOUNTAIN_ID in URI below with _id returned in Read above

[http://localhost:3000/api/update/MOUNTAIN_ID](http://localhost:3000/api/update/MOUNTAIN_ID)

![Update](img/put_update.png?raw=true "Update")


### DELETE / Delete
+ Replace MOUNTAIN_ID in URI below with _id returned in Update above

[http://localhost:3000/api/delete/MOUNTAIN_ID](http://localhost:3000/api/delete/MOUNTAIN_ID)

![Delete](img/delete.png?raw=true "Delete")
