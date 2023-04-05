# Groupe TP 3 année l'INSA 2022-2023

Author :
DO Uy Khang
Le Doan Phuoc

# To test with database

NOTE : you must also have a user to connect to sql database (we use 'root' with password : 'qwerty')
Create a database name 'TP' with a table name 'doctor' : like this structure
# DOCTOR TABLE
+------------+-----------------------------------+------+-----+---------+----------------+
| Field      | Type                              | Null | Key | Default | Extra          |
+------------+-----------------------------------+------+-----+---------+----------------+
| id         | int(11)                           | NO   | PRI | NULL    | auto_increment |
| name       | varchar(255)                      | NO   |     | NULL    |                |
| email      | varchar(255)                      | NO   | UNI | NULL    |                |
| password   | varchar(255)                      | NO   |     | NULL    |                |
| specialist | enum('heart','neuron','skeleton') | YES  |     | NULL    |                |
| gender     | tinyint(1)                        | YES  |     | NULL    |                |
| create_at  | date                              | YES  |     | NULL    |                |
+------------+-----------------------------------+------+-----+---------+----------------+


