## Table of contents

* [Overview](#overview)
* [GitHub Organization](#github-organization)
* [Galaxy](#galaxy)
* [User Guide](#user-guide)
* [Community Feedback](#community-feedback)
* [Developer Guide](#developer-guide)
* [Development History](#development-history)
* [Contact Us](#contact-us)

## Overview

*The Problem*: With many thirsty people frequenting the UH Manoa Campus to quench their thirst, it is imperative that people have access to the best avaliable water source on campus. For all those times you don’t have a water bottle and aren’t willing to pay the price for bottled water. Or maybe you aren’t sure if the water fountains in POST are better then the water fountains at Sakamaki. We bring to you an innovative new app.

*The Solution*: Introducing Water Connoisseur, for the times you don’t have a water bottle and just need to know which water fountain is the best. Water Connoisseur is an app that allows users to review and find the best water fountains on campus.

For this app, there will be a way to organize and present different water fountains around the UH Manoa campus. There will be two roles, Users, who can login to review water fountains and submit requests to have water fountains added to the list of reviewable water fountains. Admins, who will be able to login and moderate the app as well as add water fountains to the reviewable list.

Users should also be able to rate other users reviews, with a like and dislike system. With inappropriate reviews being able to be removed by Admins.

There should also be a sorting system, with top rated water fountains being able to be found easily.

## GitHub Organization
Access the UH Water Fountains GitHub Organization [here](https://github.com/uh-waterfountain), and all of its repositories.

## Galaxy
The UH Water Fountains system is deployed to Galaxy, and can be accessed [here](http://uhwaterfountains.meteorapp.com/#/).

## User Guide

### Landing Page
The [Landing Page](http://uhwaterfountain.meteorapp.com/#/) is the first page users will see.

<img src="doc/landing-page.png" alt="landing-page">

### Login and Sign Up
These pages are for signing up if you do not own an account or to login if you have an account.

[Login Page](http://uhwaterfountains.meteorapp.com/#/signin)
<img src="doc/login.png" alt="login">

[Sign Up Page](http://uhwaterfountains.meteorapp.com/#/signup)
<img src="doc/signup.png" alt="signup">

### Home Page
Once you have signed in, you should be able to view the home page. It is similar to the landing page, but you are logged into your account and now have access to the features of the application.

### Add Fountain Page
On the NavBar, there is an ["Add Fountains"](http://uhwaterfountain.meteorapp.com/#/add) link that will direct you to a form where you are able to add a fountain that is on campus. 

<img src="doc/addFountain.png" alt="add-fountain">

### Review Fountain Page
On the NavBar, there is a "Review Fountain" link that will direct you to a form where you are able to review one of the registered fountains on campus.

### List Buildings Page
On the NavBar, there is a ["List Buildings"](http://uhwaterfountains.meteorapp.com/#/list) link that will direct you to a list of buildings on campus, by clicking one of these cards it will display all the registered water fountains in the building.

<img src="doc/listBuildings.png" alt="list-buildings">

### List Fountains Page
After clicking a building card you will be shown the fountains that can be found in that building. With the reviews for each fountain being shown, from the highest rated review to the lowest rated review.

### Top Rated Reviews Page
You are able to view the top rated reviews of each water fountain on campus.

### Map Page
This page provides a map of the UH Manoa campus. The map is labeled with the names of the buildings that are included in the List Fountains page. It also consists information that shows the amount of fountains in each building.

<img src="doc/mappage.png" alt="map-page">

## Community Feedback
Issues and suggestions from users will be put here.

## Developer Guide
This section provides information of interest to Meteor developers wishing to use this code base as a basis for their own development tasks.

### Installation 
1. Install [Meteor.](https://www.meteor.com/install)

2. Visit the [UH Water Fountain's application Github page.](https://github.com/uh-waterfountain/uh-waterfountain) You can either click the “Use this template” button, download the source code as a zip file, or make a fork of the repository to create your own repository initialized with a copy of this application.
  
    However way you do it, clone your copy of the repository into your local computer.
    
3. Then, cd into the uh-waterfountain/app directory and install libraries by:

    ```
    $ meteor npm install
    ```    

4. Run the system with:

    ```
    $ meteor npm run start
    ```
    
5. You can now view the application at [http://localhost:3000](http://localhost:3000).
    
  

## Development History

### Milestone 1: Mockup Development
The goal of Milestone 1 was to create a set of HTML pages providing a mockup of the pages in the system.

Milestone 1 was managed using [UH Water Fountain Github Project Board M1:](https://github.com/uh-waterfountain/uh-waterfountain/projects/2)

<img src="doc/M1.png" alt="M1">

### Milestone 2: Improving Functionality and Quality
The goal of Milestone 2 was to improve the functionality and quality of our application beyond Milestone 1.

Milestone 2 was managed using [UH Water Fountain Github Project Board M2:](https://github.com/uh-waterfountain/uh-waterfountain/projects/3) 

<img src="doc/M2.png" alt="M2">

### Milestone 3: Final Touches
The goal of Milestone 3 was to clean up the code base and fix minor UI issues.

Milestone 3 is currently being managed using [UH Water Fountain Github Project Board M3:](https://github.com/uh-waterfountain/uh-waterfountain/projects/4)

## Contact Us
* [Bryson Yuen](https://github.com/brysonsy)
* [Gunwook Baik](https://github.com/gbaik00)
* [Sean Sumida](https://github.com/seansumida)
* [Sheena Torres](https://github.com/sheenatorres)
* [Jake Castillo](https://github.com/jakecastillo)
