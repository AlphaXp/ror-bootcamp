====================
Part 4 - SQL
====================

`Back <../index.html>`_

.. contents::

Demonstration
--------------------

* sqlite
  * If sqlite is not installed, install it::

      $ sudo apt-get install sqlite3 libsqlite3-dev

  * Create a new DB::

      sqlite bootcamp.db

* creating a table
* Inserting data
* Queries
* Table join

Read
--------------------

* Read the `w3schools SQL tutorial <http://www.w3schools.com/sql/default.asp>`_ 

Exercise 1
-------------------
* Think of the tables needed to store the Pizza Burger domain objects
* Create the file tables.sql with the creation code
* Create the file data.sql with some data insertion SQL
* Create the file list_orders.sql with the SQL query for the "list orders" action
* Create the file list_clients.sql with the SQL query for the "list clients" action
* create the file client_statistics.aql with an SQL query that show the number of orders each client in the system have made. Hint: use group_by, join, and the count() function