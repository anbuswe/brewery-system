This is a web application to search Brewery by City, Type, Name using Brewery APIs (https://www.openbrewerydb.org/documentation).

Users can provied ratings and add reviews.

Features
Users can create profile and ratings, reviews and browse nearby breweries.
user can search based on City, Type, Name.
Users can refer to other peoples ratings and reviews.
Application Stack
NodeJS - Backend
React.js - Frontend
Setup
git clone https://github.com/anbuswe/brewery-system.git
MySQL:
create database brewverse;
use brewverse;
create table users(username varchar(255),pass varchar(255),fullname varchar(255),email varchar(255));
How to run Application
npm i
npm run
localhost:3000 or use .env to set the port as required
