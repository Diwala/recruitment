Challenge for Fullstack Developer
===============================

To better assess a candidate's development skills, we would like to provide the following challenge. This is intended to be developed in a remote asyncronously way with continues communication.
It's allowed to use documentation and online resources.

Prerequisites
-------------

* [Git](https://git-scm.com/)
* Some storage of choice, [PostgresSQL](https://www.postgresql.org/), [SQLLite](https://www.sqlite.org/index.html), [MongoDB](https://www.mongodb.com/), [MySQL](https://www.mysql.com/) or any other suiting storage you find.

* [Node.js](https://nodejs.org/)
* Node.js framework of your choice (i.e. [Fastify](https://www.fastify.io/), [Express](https://expressjs.com/), [Loopback](https://loopback.io/) or any other you find suiting)

Installation
------------

Start a new repo with this README in it.
We are note merging back to this repo because this repo shall stay clean of solutions

Generate a Node.js project. You can add libraries of your choice, but be ready to describe them.

**We will not count any time spent until you have a working environment and made your choice of libs and stack**

Project description
-------------------
# Intro
You are free to solve this in any UI form you like. Remember to read the whole text and evaluation before you start any coding. It is important information there.

**Pizzeria**

The application serves the purpose of ordering pizza online.

The following entities should be created (including proper relations):

* *pizza type* - has a name and price (e.g. Margherita $5, Pepperoni $6, ...)
* *order* - has items
* *order item* - has a pizza type and quantity

On the client application, list of orders with total prices should be shown.

There should be a "Create Order" function, the user can select pizza types and amounts, add to the order, see current total, and place (save) the order.

Additionally, the following JSON API should be provided:

* list of orders
* details of an individual order

Optional features:

* meaningful model validations (e.g. item amount > 0)
* order bonuses (e.g. 5% cheaper when total over $50, 10% cheaper when total over ...)
* authentication
* tests
* whatever interesting you'd like to do

Evaluation
----------

Our goal is to find answers to those questions:

* Do you understand the chosen stack, framework and any patterns used in general?
* Can you setup interfaces that are clear and easy to use?
* Do you master your working environment?

To set a scope of the task, so we dont take too much of your time, consider the following:

* It is not important to have a fully functional application at the end, we find our way and scope along the way.
* The goals might shift during the progress as we discuss during the work flow
* The front-end does not have to be beautiful, it can even be CLI if that is what you feel comfortable with.

We just want to see at what level of engangement and knowledge you put yourself.
If you decide to do one implementation and explain the rest of future work in words and clear detail, that is also fine.

Levels of functionality:

* **basic** - items mentioned in description work
* **above average** - some optional features
* **exceptional** - getting the app to continuously build, deploy to the cloud, give a url to work with, etc.