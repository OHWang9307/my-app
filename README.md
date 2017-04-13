# Assignment 1 - ReactJS Messages Board app.

Name: hong wang

## Overview.
...... A statement of the app concept and objectives (about a half-page) ........
User can choose their own nickname and can left their messages.
The system can show all users' messages.
The system can show the time when user submited.
User can delete their messages after submit.

 . . . . . List of user features (excluding user registration and authentication) . . . . 
 
 + Feature 1 : left message 
 + Feature 2 : left nickname
 + Feature 3 : give the messages sending time till now
 + etc


## Installation requirements.
. . . .  List of software used to develop the app . . . . . . . 
+ ReactJS v15.3.0
+ Bootstrap 4
+ create-react-app tool
+ AJAX
+ etc 

. . . . . . Also, explain (to a third party) what steps one must take to run your app after cloning it from the repository, e.g. any non-standard software installation; any environment setup; how to start app; where to view app in browser . . . . . . . At its simplest this may just be: 
## TO run the app

+ npm install
+ npm start

## Data Model Design.

Diagram of app's data model (see example below) AND/OR a sample of the test data used (JSON or equivalent).

![][image1]

Use meaningful sample data. Briefly explain any non-trivial issues.

## App Component Design.

A diagram showing the app's hierarchical component design (see example below). 

![][image2]

## UI Design.

. . . . . Screenshots of app's views (see example below) with appropriate captions (user regeneration and login views, if implemented, can be omitted) . . . . . . . 

![][image3]

## Routing.
. . . . List each route supported and state the associated view . . . . . 

+ /messages - displays all published messages
+ etc

## Extra features

. . . . . Briefly explain any non-standard features, functional or non-functional (e.g. user registration, authentication) developed for the app . . . . . .  

## Independent learning.

Using AJAX as a method to auto refresh the time when user submited.

[image1]: ./model.png
[image2]: ./design.jpg
[image3]: ./screen.png