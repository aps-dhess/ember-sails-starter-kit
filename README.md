ember-sails-starter-kit
======



Prerequisites
-------------

You will need the following things properly installed on your system.
* [Git](http://git-scm.org)
* [Node.js (with NPM)](http://nodejs.org/)
* [Bower](http://bower.io/)
* [Ember CLI](http://ember-cli.com/)
* [Sails.js](http://sailsjs.org/)
* [PhantomJS (recommended)](http://phantomjs.org/)

Installation
------------
```
git clone https://github.com/dchess/ember-sails-starter-kit.git
cd server
npm install
cd ..
cd client
npm install
bower install
```

Database Configuration
--------------------
This repo is pre-configured to use MS SQL server, but you'll need to add the environment variables for your instance.
```
$env:DB_HOST="<your host address>"
$env:DB="<your database name>"
$env:DB_USER="<your sql user account name>"
$env:DB_PASS="<your sql user account password>"
```

Running/Development
--------------------
* ```sails lift```
* Visit your api server at [http://localhost:1337](http://localhost:1337)
* ```ember serve```
* Visit your app at [http://localhost:4200](http://localhost:4200)
