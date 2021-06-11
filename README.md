# Summer program: Software design - candidate system

##### The aim of this project is to let a high school student to get the first expericece of designing a software. Python is the best language to do the proof of concept, and to do prototyping.
##### This is a real world problem. As a company, we need to interview the candidates at all times, we want the records of the candidates can be stored into a database. And we want some Python APIs to help us get the information of the candidates.
#### Example requirements for Python API:
1. Store a canditate's information, including but not limited to: id, name, sex, birthdate, education, skill sets, the score we rank for each candidate, into the database.
2. Provide an API to let us get the full list of all the candidates.
3. Provide an API to let us get the top N highest scorers.
4. Provide an API to let us fetch the information of one candidate by the name.

## Learning Goals
1. Learn the notion of API.
2. Learn the basic concept of a database, and the basic knowledge of SQL.
3. Learn how to connect a database by Python.
4. Learn how to do object oriented software design.

## Expected Result
1. Design the schema of a database table, and apply the reasonable datatype for each field.
2. Design Python class which could be the data object, to help load the information we fetch from the database.
3. Design APIs, to help people not need to interact with database directly, they can simply call the API to get the result they want.

## References
1. https://www.jetbrains.com/pycharm/download/#section=mac
2. https://www.w3schools.com/mysql/
3. https://dev.mysql.com/doc/connector-python/en/connector-python-example-connecting.html
4. https://brew.sh/
5. https://stackoverflow.com/questions/4359131/brew-install-mysql-on-macos
6. https://realpython.com/python3-object-oriented-programming/
7. https://realpython.com/python3-object-oriented-programming/
##### Please notice: a good programmer can know every thing when he/she has the Internet access, please go to search anything you want to know by Google.

## Timeline
#### Week1: Install the python IDE, mysql on the macbook, learn the basic concept of object-oriented programming.
#### Week2: Learn the basic SQL operations, create the table on the database, with a well-designed schema.
#### Week3: Figure out how to load the data we fetch from the database to an Python object, how to connect the mysql database by Python.
#### Week4: Implement the APIs mentioned in the Requirements above.
