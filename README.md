# Bucket List API
[![Build Status](https://travis-ci.org/Gidraff/BucketList_API.svg?branch=api-endpoints)](https://travis-ci.org/Gidraff/BucketList_API)[![Coverage Status](https://coveralls.io/repos/github/Gidraff/BucketList_API/badge.svg?branch=master)](https://coveralls.io/github/Gidraff/BucketList_API?branch=master)

This is a Bucket List Application. It lets you keep track of activities that you want to do before you bite the dust. It uses flask-sqlalchemy, flask and postgres database for backend.

|  Endpoints  | Functionalities  |  Public Access |
|:-------------|:------------------|----------------|
| `POST /auth/register` | Registers a user |  True |
| `POST /auth/login`| Logs in a user | TRUE |
| `POST /bucketlists/`| Create a new bucket list | FALSE |
| `GET /bucketlists/`| List all the created bucket lists | FALSE |
| `GET /bucketlists/<id>`| Get single bucket list | FALSE |
| `PUT /bucketlists/<id>/`| Update this bucket list | FALSE |
| `DELETE /bucketlists/<id>`| Delete this single bucket list | FALSE |
| `POST /bucketlists/<id>/items/`| Create a new activity in bucket list | FALSE |
| `PUT /bucketlists/<id>/items/<item>`| Update a bucket list activity | FALSE |
| `DELETE /bucketlists/<id>/items/<item>`| Delete an activity from a bucket list | FALSE |

#### HTTP verbs or methods used in the Bucket List Api :

| Methods(verbs) | Description |
|:----------------|:-------------|
|`GET` | Retrieves a resource(s) |
|`POST` | Creates a resource(s) |
|`PUT` | Edits or creates an existing resource(s) |
| `DELETE` | Deletes an existing resource(s)


### Status code expected:

| Status code | Description |
|:-------------|-------------|
| `2xx`  |  successful! |
| `3xx` | Redirection |
| `4xx` | Client error |
| `5xx` | Server error |


#### Bucket List Api(CRUD) Features:

* Register users
* Login Users
* Create and delete Bucket List
* Add and delete Bucket List items


#### Feature Completed:

* Register Users
* Login Users
* Create BucketList
* Edit BucketList
* Delete a BucketList
* Add item
* Edit item
* delete item
* Logout Users
* Token Based Authentication

#### Work in Progress [WIP]:


* Pagination
* Search
* Hosting the app to Heroku

#### Pre-requisite:
 * Python3.6
 * Flask
 * Postgres


 #### Installation Guide lines:
To get started with BucketList App Api:
 * clone this application from https://github.com/Gidraff/BucketList_API.git
 * cd into BucketList_API
* Create a virtual environment `Virtualenv ven`
* Run `pip install > requirements` to install all dependencies required by the app.
* Run `python manage.py db init`, `python manage.py db migrate` and `python manage.py db upgrade` to setup the database up and running.

Now to run the app, run `python run.py` . This will start up the server and you can proceed using the app.

The only thing left is for you to ENJOY!!

