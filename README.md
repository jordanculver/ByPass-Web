ByPass-Web
=======================================

HackWars 2017 team FN-1337's simple web service for hosting static html pages for the iOS client.

Table of Contents
=================
* [Installation](#installation)
* [Run Service Locally](#run-service-locally)
* [Run Service on Bluemix](#run-service-on-bluemix)
* [Static pages](#static-pages)

Installation
============

Clone repository:

    git clone https://github.com/jordanculver/ByPass-Web.git

Go into cloned folder and install node dependencies

    cd ByPass-Web

    npm install


Run Service locally
==================
To run this locally change directory to ByPass-Web/ then:

    npm start
    or
    sails lift

Then open [http://localhost:3000](http://localhost:3000)

Run Service on Bluemix
======================
[Download Cloud Foundry CLI](https://github.com/cloudfoundry/cli#downloads)
    
    cf login -a https://your-bluemix-endpoint.ng.bluemix.net
    cf push YourCustomAppName -m 512MB

Static pages
============

- [Front page](http://localhost:3000/default.html)
- [Successfully boarded flight page](http://localhost:3000/boarded.html)
- [Failed to board flight page](http://localhost:3000/failure.html)

