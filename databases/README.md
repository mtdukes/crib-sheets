# Databases
Here's a running list of stuff you might need doing database work.

##Software

- MySql (free)
The underlying server you'll run on your machine.

- Sequel Pro (free)
This is the GUI you need

##Logging in
Using Sequel Pro, the connection details are as follows to log into your local instance of MySql

- Host: localhost
- Username: root

Leave everything else blank.

##Common commands

Create a calculated column in an existing table

```
UPDATE table_name SET new_column = column_one * column_two
```
