# Django API with Django Rest Framework and AngularJS-Resource

This sample project is how to get started with Django Rest Framework and AngularJS.

## Dependencies

To setup and run the sample code, you're going to need `npm` from NodeJS available to install the frontend code.

## Setup

### Docker

If you have a docker host, you can simply use `docker-compose` to build the example, then open [http://localhost](http://localhost):

```
docker-compose up
```

### Manual

You're encouraged to setup a `virtualenv` to work in prior to configuring the dependencies.

1. Install Python Requirements

        pip install -r requirements.txt
        python setup.py develop

2. Install Bower + Grunt

		npm install -g grunt-cli bower

3. Install Assets

        npm install
        bower install

4. Compile Assets

        grunt

5. Setup the Database

        make create_database; make make_fixtures

6. Run the Server

        ./manage.py runserver

