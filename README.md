# Book Search Engine 

## Table of Contents
* [Description](#Description)
+ [Link to deployed app](#link-to-deployed-app)
- [Screenshots](#screenshots)
* [Refactoring Process](#refactoring-process)

## Description

This is a fully functioning Google Books API search engine built with a RESTful API, and refactored to be a GraphQL API built with Apollo Server. The app was built using the MERN stack, with a React front end, MongoDB database, and Node.js/Express.js server and the Google Books API. 

Create an account, login and get searching! You can save your favorite books to your profile.

## Link to deployed app
https://blooming-anchorage-96351.herokuapp.com/

## Screenshots
![Screenshot 2020-10-18 230729](https://user-images.githubusercontent.com/65680645/96397475-a15ea380-1197-11eb-97e5-519ff7066003.png)
![Screenshot 2020-10-18 231036](https://user-images.githubusercontent.com/65680645/96397478-a3c0fd80-1197-11eb-9268-2105edb8b186.png)

## Refactoring Process

* First, I set up an Apollo Server to use GraphQL queries and mutations to fetch and modify data, replacing the existing RESTful API.
+ Then, I modified the existing authentication middleware so that it works in the context of a GraphQL API.
- I created an Apollo Provider so that requests can communicate with an Apollo Server.
* Then I deployed the application to Heroku.
