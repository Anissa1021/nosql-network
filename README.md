# NOSQL-Social Network

## Description
For this application you are able to share what you are thinking as well as add and delete friends. This is all back end on Insomnia and there is no front end to this, however you are still able to create, delete, and update users and their thoughts. 
## User Story
```
AS A social media startup
I WANT an API for my social network that uses a NoSQL database
SO THAT my website can handle large amounts of unstructured data
```
## Acceptance Criteria
```
GIVEN a social network API
WHEN I enter the command to invoke the application
THEN my server is started and the Mongoose models are synced to the MongoDB database
WHEN I open API GET routes in Insomnia for users and thoughts
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia
THEN I am able to successfully create, update, and delete users and thoughts in my database
WHEN I test API POST and DELETE routes in Insomnia
THEN I am able to successfully create and delete reactions to thoughts and add and remove friends to a user’s friend list
```
## Usage
1. Install with `npm i`
2. Start server `npm start`

## Example
https://drive.google.com/file/d/1j-xV2zMg-tEn4VE7UDFIukKBs_WDv2Jq/view?usp=sharing
## Tech Used
- `Express.js`
- `Mongoose`
- `Insomnia`
