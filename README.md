# KnowItAll
MERN stack project

KnowItAll is an application that allows you to challenge your friends to see who’s right. 
Users can see how they rank against friends, track challenges, and see fact challenges in their area.

## Background and Overview
When you are hanging out with a friend and they say something totally off, you kindly correct them. However, they’re pretty sure their right and your wrong. What do you do? Settle it by googling of course. Well, what if you could track all these little challenges. KnowItAll will do it for you! Type in your question and get served the most relevant google and wiki results. Declare an official round winner, and you’ll be able to look back on all your proudest and most idiotic moments!

This will need:
* Make and app that collects data
* Database to store user and search query data
* Integrate Google and Wikipedia APIs
* Construct an app that presents the accumulation resulting matches in a interesting and interactive manor
* Decide how to best facilitate connecting users during challenges, and complexity of handling match winner logic

## Functionality and MVP
* Application with landing page modal for user signup/login
* User Auth
* Page for quickly connecting(challenging) friends, additionally leverage page to reflect leaderboard stats
* Once challenge form has been submitted, serve google and wikipedia search results. Ensure a winner is selected at the end of each challenge. Visual of winner.
* Stats page of prior challenges
* Feed of challenges in your area with comment functionality. Filter to your challenges, your friends challenges, recent challenges, local challenges.
* Production README
#### Bonus Features
* Suggest winnder based on search results of challenge
* Allow challenge functionality without sign-in
* Filtering on stats page

## Technologies and Technical Challenges
KnowItAll’s core application is a streamlined search API of google and wiki results, with a backend built on MongoDB to save user search queries and resulting scores between users. The database will be populated by user input. 

**Web application**

**Google/Wikipedia API**

**Backend: MongoDB/Express**

**Frontend: React/Node.js and D3 visualization library**

### Web Application
The web application will need to facilitate user login and auth. The application will need multiple routes to facilitate the collection and presentation of data both from the database and connected APIs.

### Technical Challenges
Ensuring search queries are compatible with two APIs (Goolge & Wikipeadia). Ensuring returned results of each API are integrated into one response to the user. Testing for acceptable speed of processing and formatting API results, so as not to noticeably interrupt user experience.

#### Things accomplished over the weekend
Things Accomplished Over the Weekend
We worked through the MERN curriculum online and created a User Auth system following the new guidelines. We also generated the frontend skeleton for the app and will begin to add functionality tomorrow.

### Group Members and Work Breakdown

##### Day 1 - Saturday 5/11

##### Day 2 - Sunday 5/12

##### Day 3 - Monday 5/13
**Alissa** 
* I can work on building out some of the front end components. I was planning on starting with the login/signup page and the main index feed which will hold a list of previously asked questions and comments. 
* I think another high priority is the google api page where people will be asking the questions. Did we decide on making this a separate page accessible via a button on the index page?  
* Seems like we will need routes to the basic login page but also depends on whether or not we’re using a modal 

**Brett**
* Flesh out and implement necessary routes along with the accompanying payload. Test.  Need to finalize what the user login flow will be and which pages link to where.  Figure out how to get google API hooked up.
* Link backend routes and Google API to as many frontend components as possible
##### Day 4 - Tuesday 5/14

##### Day 5 - Wednesday 5/15







