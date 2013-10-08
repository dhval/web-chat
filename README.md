Web-Chat-Admin
===============

A pure Java (with apacahe depndencies) based project to automate administration of chat server.


What it does:
-------------

Connects to server using apache http client, looks for specific users or keywords, intreprets those as commands and executes them.


Saving State:
-------------

Use HSQLDB (file based) for maintaing states, and result of other commands.

