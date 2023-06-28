# NoSQL-SN-API-SA
## Table of Contents
* [User Story](#user-story)
* [Acceptance Criteria](#acceptance-criteria)
* [Description](#description)
* [Installation](#installation)
* [Walkthrough Video](#walkthrough-video)
* [Questions](#questions)

## User Story
AS A social media startup
I WANT an API for my social network that uses a NoSQL database
SO THAT my website can handle large amounts of unstructured data

## Acceptance Criteria
GIVEN a social network API

WHEN I enter the command to invoke the application

THEN my server is started and the Mongoose models are synced to the MongoDB database
WHEN I open API GET routes in Insomnia for users and thoughts
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia
THEN I am able to successfully create, update, and delete users and thoughts in my database
WHEN I test API POST and DELETE routes in Insomnia
THEN I am able to successfully create and delete reactions to thoughts and add and remove friends to a user’s friend list

## Description
This is a Social Network API that uses a NoSQL database. It allows users to create, update, and delete users, thoughts, and reactions. It also allows users to add and remove friends. This API uses Express.js for routing, MongoDB for the database, and Mongoose for the ODM.

## Installation
1. Clone this repository.
2. Install dependencies with `npm install`.
3. Run `npm start` to start the server.

## Walkthrough Video

See [my walkthrough video](https://drive.google.com/file/d/1ThiFHRBzAu2HX5NR7PfBa8Wwqy6Emd15/view) to see how this works!

## Questions
If you have any questions, please contact me at the email below.

sandregg2@gmail.com

