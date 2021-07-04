# DjangoRestApiMongoDB
In this, we’re gonna create Python 3/Django & MongoDB CRUD example with Django Rest Framework for building Rest Apis.

# Django MongoDB CRUD Rest API overview
We will build Rest Apis using Django Rest Framework that can create, retrieve, update, delete and find Tutorials by title or published status.

First, we setup Django Project with a MongoDB Connector. Next, we create Rest Api app, add it with Django Rest Framework to the project. Next, we define data model and migrate it to the database. Then we write API Views and define Routes for handling all CRUD operations (including custom finder).

The following table shows overview of the Rest APIs that will be exported:

# Methods	Urls	Actions
GET	      api/tutorials	              get all Tutorials
GET	      api/tutorials/:id	          get Tutorial by id
POST	    api/tutorials	              add new Tutorial
PUT	      api/tutorials/:id	          update Tutorial by id
DELETE	  api/tutorials/:id	          remove Tutorial by id
DELETE	  api/tutorials	              remove all Tutorials
GET	      api/tutorials/published	    find all published Tutorials
GET	      api/tutorials?title=[kw]	  find all Tutorials which title contains 'kw'

# Technology

* Python 3.7
* Django 2.1.15
* Django Rest Framework 3.11.0
* djongo 1.3.1
* django-cors-headers 3.2.1
* MongoDB 3.4 or higher
