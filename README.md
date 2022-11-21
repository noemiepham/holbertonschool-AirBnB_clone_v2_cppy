
# AirBnB clone - MySQL

-   Amateur
-   By:  Guillaume
-   Weight:  2
-   Project to be done in teams of  2  people  (your team:  Noémie Pham, Chong Leang Ueng)
-   Your score will be updated once you launch the project review.

## Background Context

Environment variables will be your best friend for this project!

-   `HBNB_ENV`: running environment. It can be “dev” or “test” for the moment (“production” soon!)
-   `HBNB_MYSQL_USER`: the username of your MySQL
-   `HBNB_MYSQL_PWD`: the password of your MySQL
-   `HBNB_MYSQL_HOST`: the hostname of your MySQL
-   `HBNB_MYSQL_DB`: the database name of your MySQL
-   `HBNB_TYPE_STORAGE`: the type of storage used. It can be “file” (using  `FileStorage`) or  `db`  (using  `DBStorage`)

## Resources

**Read or watch**:

-   [cmd module](https://intranet.hbtn.io/rltoken/n2iuMmutfCZmeMqbeBnlaw "cmd module")
-   **packages**  concept page
-   [unittest module](https://intranet.hbtn.io/rltoken/nUpQTzwnNi_c8AIKoBdrmw "unittest module")
-   [args/kwargs](https://intranet.hbtn.io/rltoken/m8vYyTQi5-raOlUJJ9NItg "args/kwargs")
-   [SQLAlchemy tutorial](https://intranet.hbtn.io/rltoken/2DZHkwnlEmv4Iy7hufh3Xg "SQLAlchemy tutorial")
-   [How To Create a New User and Grant Permissions in MySQL](https://intranet.hbtn.io/rltoken/OpbgfN52Xc5Vrwug9jAb5A "How To Create a New User and Grant Permissions in MySQL")
-   [Python3 and environment variables](https://intranet.hbtn.io/rltoken/VHWw0H0LGwlpUBCI1qkPSQ "Python3 and environment variables")
-   [SQLAlchemy](https://intranet.hbtn.io/rltoken/3rDo_Lb9DFRufb4Zh3JbdQ "SQLAlchemy")
-   [MySQL 8.0 SQL Statement Syntax](https://intranet.hbtn.io/rltoken/9dZyqKjKVADhWytWrK8F6A "MySQL 8.0 SQL Statement Syntax")
-   [AirBnB clone - ORM](https://intranet.hbtn.io/rltoken/ZsjgMgJW7i6QXz6LlRP78Q "AirBnB clone - ORM")

## Learning Objectives

At the end of this project, you are expected to be able to  [explain to anyone](https://intranet.hbtn.io/rltoken/LAyje3OPhToMqWM-vuzUzA "explain to anyone"),  **without the help of Google**:

### General

-   What is Unit testing and how to implement it in a large project
-   What is  `*args`  and how to use it
-   What is  `**kwargs`  and how to use it
-   How to handle named arguments in a function
-   How to create a MySQL database
-   How to create a MySQL user and grant it privileges
-   What ORM means
-   How to map a Python Class to a MySQL table
-   How to handle 2 different storage engines with the same codebase
-   How to use environment variables

## Requirements

### Python Scripts

-   Allowed editors:  `vi`,  `vim`,  `emacs`
-   All your files will be interpreted/compiled on Ubuntu 20.04 LTS using python3 (version 3.8.5)
-   All your files should end with a new line
-   The first line of all your files should be exactly  `#!/usr/bin/python3`
-   A  `README.md`  file, at the root of the folder of the project, is mandatory
-   Your code should use the pycodestyle (version 2.7.*)
-   All your files must be executable
-   The length of your files will be tested using  `wc`
-   All your modules should have documentation (`python3 -c 'print(__import__("my_module").__doc__)'`)
-   All your classes should have documentation (`python3 -c 'print(__import__("my_module").MyClass.__doc__)'`)
-   All your functions (inside and outside a class) should have documentation (`python3 -c 'print(__import__("my_module").my_function.__doc__)'`  and  `python3 -c 'print(__import__("my_module").MyClass.my_function.__doc__)'`)
-   A documentation is not a simple word, it’s a real sentence explaining what’s the purpose of the module, class or method (the length of it will be verified)

### Python Unit Tests

-   Allowed editors:  `vi`,  `vim`,  `emacs`
-   All your files should end with a new line
-   All your test files should be inside a folder  `tests`
-   You have to use the  [unittest module](https://intranet.hbtn.io/rltoken/nUpQTzwnNi_c8AIKoBdrmw "unittest module")
-   All your test files should be python files (extension:  `.py`)
-   All your test files and folders should start by  `test_`
-   Your file organization in the tests folder should be the same as your project: ex: for  `models/base_model.py`, unit tests must be in:  `tests/test_models/test_base_model.py`
-   All your tests should be executed by using this command:  `python3 -m unittest discover tests`
-   You can also test file by file by using this command:  `python3 -m unittest tests/test_models/test_base_model.py`
-   All your modules should have documentation (`python3 -c 'print(__import__("my_module").__doc__)'`)
-   All your classes should have documentation (`python3 -c 'print(__import__("my_module").MyClass.__doc__)'`)
-   All your functions (inside and outside a class) should have documentation (`python3 -c 'print(__import__("my_module").my_function.__doc__)'`  and  `python3 -c 'print(__import__("my_module").MyClass.my_function.__doc__)'`)
-   We strongly encourage you to work together on test cases, so that you don’t miss any edge cases

### SQL Scripts

-   Allowed editors:  `vi`,  `vim`,  `emacs`
-   All your files will be executed on Ubuntu 20.04 LTS using  `MySQL 8.0`
-   Your files will be executed with  `SQLAlchemy`  version  `1.4.x`
-   All your files should end with a new line
-   All your SQL queries should have a comment just before (i.e. syntax above)
-   All your files should start by a comment describing the task
-   All SQL keywords should be in uppercase (`SELECT`,  `WHERE`…)
-   A  `README.md`  file, at the root of the folder of the project, is mandatory
-   The length of your files will be tested using  `wc`

### GitHub

**There should be one project repository per group. If you clone/fork/whatever a partner’s project repository with the same name before the second deadline, you risk a 0% score.**

## More Info

![](https://s3.amazonaws.com/intranet-projects-files/concepts/74/hbnb_step2.png)
