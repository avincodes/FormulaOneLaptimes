
Requirements

`$ pip3 install pyqt5 requests matplotlib bitarray pymysql pyqtchart`

You may set up a native MySQL environment, and create the needed database via the .sql file provided by ergast.com , but since it is no easy job, I've used the [mysql2sqlite](https://github.com/dumblob/mysql2sqlite) to generate a sqlite db, and you may download the db that comes with 0.2.1 version
[here](https://github.com/Hycdog/F1_Analyz/releases/download/v0.5.5/f1.db).

Currently some data in 1996 is not available.


Changes made to the database:

    
    Aug 12 2019:

    Add missing pitstop for car 44 in race 1020
    Add table stint

After installing the requirements, and having a f1.db file under project directory, you may run

`$ python3 gui.py`
   
to start the software.

Current version: 0.7.0 

The project is in a very early stage, and a lot of features and algorithms are needed. Any king of help is greatly appreciated!

## Code

The GUI is made with the python3 implementation of Qt -- PyQt5.

The Initial thought of this project is to take a deeper dive into the F1.
