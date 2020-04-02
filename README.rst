InfluxDB-Python (With Relay)
============================

InfluxDB-Python is a client for interacting with InfluxDB_. The main source of the library is found at https://github.com/influxdata/influxdb-python.

Development of this library is maintained by and the relay features was edited by me:

+-----------+-------------------------------+
| Github ID | URL                           |
+===========+===============================+
| @aviau    | (https://github.com/aviau)    |
+-----------+-------------------------------+
| @xginn8   | (https://github.com/xginn8)   |
+-----------+-------------------------------+
| @sebito91 | (https://github.com/sebito91) |
+-----------+-------------------------------+

.. _readme-about:

InfluxDB is an open-source distributed time series database, find more about InfluxDB_ at https://docs.influxdata.com/influxdb/latest


.. _installation:

Simply clone the library and enter the folder and execute `pip install .`

.. _features:

Currently, all the functions edited causes the whole library to be workable only with the influxdb-relay architecture by https://github.com/strike-team/influxdb-relay
which is highly maintained by the developers. They added a /admin endpoint in order to create database (for e.g) to be used in all 3 instances rather than simply using 
for just 1 instance like the default library assumes. 

With this, I edited the library requests to call to the /admin endpoint instead to do these administrative tasks. Everything remains the same, you can refer to the docs
by the influxdata team that created the influxdb-python files in regards to each individual APIs, for the relay calls, simply add relay_create_database for example to create
the database for the instances that you have set up.

