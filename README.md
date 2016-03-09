# node-js-getting-started

A barebones Node.js app using [Express 4](http://expressjs.com/).

This application supports the [Getting Started with Node on Heroku](https://devcenter.heroku.com/articles/getting-started-with-nodejs) article - check it out.

## Running Locally

Make sure you have [Node.js](http://nodejs.org/) and the [Heroku Toolbelt](https://toolbelt.heroku.com/) installed.

```sh
$ git clone git@github.com:heroku/node-js-getting-started.git # or clone your own fork
$ cd node-js-getting-started
$ npm install
$ npm start
```

Your app should now be running on [localhost:5000](http://localhost:5000/).

## Deploying to Heroku

```
$ heroku create
$ git push heroku master
$ heroku open
```
or

[![Deploy to Heroku](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy)

## Documentation

For more information about using Node.js on Heroku, see these Dev Center articles:

- [Getting Started with Node.js on Heroku](https://devcenter.heroku.com/articles/getting-started-with-nodejs)
- [Heroku Node.js Support](https://devcenter.heroku.com/articles/nodejs-support)
- [Node.js on Heroku](https://devcenter.heroku.com/categories/nodejs)
- [Best Practices for Node.js Development](https://devcenter.heroku.com/articles/node-best-practices)
- [Using WebSockets on Heroku with Node.js](https://devcenter.heroku.com/articles/node-websockets)

#The Dead-Simple Step-by-Step Guide for Front-End Developers to Getting Up and Running with Node.JS, Express, Jade, and MongoDB

A tutorial and complete sample project for Front-End developers showing how to get Node, Express and Jade up and running, connected to MongoDB, and reading from / writing to the database.

*New: Completely Updated for Express 4.0 based code, with Generator-Express Scaffolding*

## Quickstart

[Visit the tutorial online](http://cwbuecheler.com/web/tutorials/2013/node-express-mongo/). The rest of the project is provided just to show the functioning finished results. The tutorial will show you how to build all of this stuff, from downloading Node all the way to the end.

If you want to run this example code, you will need to do an NPM Install, as the node_modules directory has been removed from this repository.


## Author

Christopher Buecheler is a front-end developer for a small San Francisco startup. Previously he's worked for companies like GameSpy, OkCupid, Crispy Gamer, and Comcast. You can visit him at [his website](http://cwbuecheler.com).


## Contents

* /public - static directories suchs as /images
* /routes - route files for tutorial project
* /views - views for tutorial project
* README.md - this file
* app.js - central app file for tutorial project
* package.json - package info for tutorial project
