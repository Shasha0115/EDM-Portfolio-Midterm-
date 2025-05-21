## Finals Lab Task 6. MongoDB Practice

Create Database

![Sample Output](images/Q1.png)

Insert Documents

![Sample Output](images/Q1.png)

Query / Find Documents

- Task 1
db.movies.find()

![Sample Output](images/Q1.png)

- Task 2
db.movies.find({writer:"Quentin Tarantino"})

![Sample Output](images/Q1.png)

- Task 3
db.movies.find({actors:"Brad Pitt"})

![Sample Output](images/Q1.png)

- Task 4
db.movies.find({franchise:"The Hobbit"})

![Sample Output](images/Q1.png)

- Task 5
db.movies.find({year:{$gt:"1990", $lt:"2000"}})

![Sample Output](images/Q1.png)

- Task 6
db.movies.find({$or:[{year:{$gt:"2010"}},{year: {$lt:"2000"}}]})

![Sample Output](images/Q1.png)
