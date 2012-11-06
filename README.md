DemoAPI
=======

This is a Restful API for Doing basic CRUD operations on a table developed on Django.
This is just simple use of Django to interact with database.
API will return data in JSON encoded form.
There is an interface also present to test the API.
URIs are as follows:
1. /api/customer/read/{id(can be alphanumeric)}
2. /api/customer/delete/{id(can be alphanumeric)}
3. /api/customer/create(with post data)
4. /api/customer/create(with post data to update existing record)
API data will be available to logged in users only.