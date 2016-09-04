# Ticketator

Ticketator is a simple ticketing system developed in Python, based on Django Framework.
It is inspired in some features of Jira and other ticketing systems commonly used by IT Departments.

![alt tag](https://dl.dropboxusercontent.com/u/13983419/index.png)

Ticketator behaviour is based basically, in Users, Groups and Queues. 

You can define rights to let users interact with tickets on a queue in a singular way: by example, you can define that users on a group can create new tickets, but no comment these tickets, or simply, not update a ticket once created.

Give a try to Ticketator, and give us your feedback!


### Dependencies

* [Django] 1.9 or greater
* Postgres or similar (as supported by Django ORM)
* [django-colorfield] 
* [django-extensions] 

### Installation
```sh
git clone https://github.com/sabueso/ticketator.git
```
Once installed, satisfy some dependencies manually
```sh
pip install django-colorfield
pip install django-extensions
```


### Docker demo
Docker image to test Ticketator without effort
```sh
TODO:
```
### Disclaimer

Ticketator is under active developement and some areas could not be working as expected. Please, let you free to comment it constructively under the "Issue" area on Github.

### Todos

 - Write Tests
 - A lot of more things

License
----
TODO


**Free Software, Hell Yeah!**

[//]: # (These are reference links used in the body of this note and get stripped out when the markdown processor does its job. There is no need to format nicely because it shouldn't be seen. Thanks SO - http://stackoverflow.com/questions/4823468/store-comments-in-markdown-syntax)


   [Django]: <https://www.djangoproject.com/download/>