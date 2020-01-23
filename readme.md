# paperclips - Bartering Application

![paperclips](./client/dist/assets/images/logo_purple.png)

paperclips is a bartering application developed by a team of 7 software engineers.

## Table of Contents

1. [InAction](#inaction)
2. [UserStories](#userstories)
3. [Stack](#stack)
4. [GetStarted](#getstarted)
5. [Reflections](#reflections)
6. [Contributors](#contributors)
7. [RelatedProjects](#relatedprojects)

## InAction

Home and Login screens
![home](./client/dist/assets/media/paperclips-home-login.gif)

Signup screen
![signup](./client/dist/assets/media/paperclips-signup.gif)

Feed screen
![feed](./client/dist/assets/media/paperclips-feed.gif)

Profile screens
![profile1](./client/dist/assets/media/paperclips-profile1.gif)
![profile2](./client/dist/assets/media/paperclips-profile2.gif)

Messages screen
![messages](./client/dist/assets/media/paperclips-messages.gif)


# UserStories

## Implemented

### Signup and Login

- As a user, I want to signup and login to the application, with information about my account stored and re-accessible.

### Navigation Bar

- As a user, I want a navigation bar on the bottom that is easily accessible with different pages I may frequent.
- As a user, I want the navigation bar to stay on the bottom, out of sight, and fold out when I need to use it.
- As a user, I expect to be redirected to the login or signup page if I am a new or returning user through the navigation bar or home screen.
- As a user, I want to be able to press a back button to direct myself to the previous page I was on.
- As a user, I want to be redirected to the home screen upon interacting with the logo on the navigation bar.

### User Profile Page

- As a user, I want to be able to view my name, profile picture, username, city and state, and past offers in the user profile page.
- As a user, I want to be able to view items I have uploaded for offers, active offers, or upload items I wish to offer/trade.
- As a user, I want to be able to see the details of my past offers, and see more past offers on a separate page should there be more than 4 past offers.

### Feed Page

- As a user, I want to search for items of interest and offer an item(s) to trade items.
- As a user, I want to search items by keyword, and filter by item value or date of offer post.

### Item Details Page

- As a user, I want to view item details when selecting an item, including picture(s), value, description, and posted date.
- As a user, I want to make an offer from the item details page should I be interested.

### Make Offer Page

- As a user, I want to view the item I have chosen, along with its value.
- As a user, I want to view the items available to me to trade, and add to my offer.
- As a user, I want to view the items I am offering, send a message with the offer, and send my offer to the owner.
- As a user, I want to go to the message inbox, view my offers, or navigate to the home page upon making an offer.

### Message Inbox

- As a user, I want a concise view of various message threads that I am involved in.
- As a user, I want to be able to expand or condense each message thread with interaction.
- As a user, I want to be able to send a reply that persists when I exit the app and return.
- As a user, I want to see the username of who I am talking to, the date and time of the message, and the message body.

### Active and Past Offers

- As a user, I want to view the offers I've made and the offers I've received in the active offers page, with the option of cancelling.
- As a user, I want to view the images, names, and values of items of the offers that are both active and past.
- As a user, I want to be able to accept or reject offers that I have receieved.

### Up For Trade Page

- As a user, I want to be able to see a list of offers that are currently active.
- As a user, I want to be able to search the list of active offers by keyword.
- As a user, I want to be able to view details of an item upon interaction.

## Coming Soon

- As a user, I want an authentication system that utilizes hashes and salt passwords.
- As a user, I want to filter item searches by location.
- As a user, I want offers I have accepted or rejected to be sorted accordingly.

# Stack

<table>
  <tr>
    <td align="center">Front-end</td>
    <td align="center">Back-end</td>
    <td align="center">Deployment</td>
  </tr>
  <tr>
    <td align="center"><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/a/a7/React-icon.svg/1280px-React-icon.svg.png" alt="React" title="React" width="80px"/></td>
    <td align="center"><img src="https://www.brandeps.com/logo-download/N/Node-JS-logo-vector-01.svg" alt="Node.js" title="Node.js" width="80px"/></td>
    <td align="center"><img src="https://miro.medium.com/max/736/1*Fd6rk1k1FHPZcg4aK_OXtQ.png" alt="AWS Elastic Beanstalk" title="AWS Elastic Beanstalk" width="80px"/></td>
  </tr>
  <tr>
    <td align="center"><img src="https://raw.githubusercontent.com/reduxjs/redux/master/logo/logo-title-dark.png" alt="Redux" title="Redux" width="60px"/></td>
    <td align="center"><img src="https://buttercms.com/static/images/tech_banners/ExpressJS.png" alt="Express" title="Express" width="60px"/></td>
    <td align="center"><img src="https://i0.wp.com/codeandcoffee.us/wp-content/uploads/2018/07/s3.png?fit=387%2C375" alt="AWS-S3" title="AWS-S3" width="80px"/></td>
  </tr>
  <tr>
    <td align="center"><img src="https://sdtimes.com/wp-content/uploads/2018/01/bootstrap-stack-490x412.png" alt="Bootstrap" title="Bootstrap" width="80px"/></td>
    <td align="center"><img src="https://zdnet4.cbsistatic.com/hub/i/r/2018/04/19/092cbf81-acac-4f3a-91a1-5a26abc1721f/resize/370xauto/ce84e38cb1c1a7c5a2c9e4c337e108ba/postgresql-logo.png" alt="PostgreSQL" title="PostgreSQL" width="80px"/></td>
    <td align="center"><img src="https://i2.wp.com/sysadminxpert.com/wp-content/uploads/2017/09/rds-logo.jpg?fit=313%2C200&ssl=1" alt="AWS-RDS" title="AWS-RDS" width="80px"/></td>
  </tr>
</table>

## Front-End

Mobile-first development was applied based on the iPhone X. Material Design for Bootstrap was used for styling, while state was stored across paperclips with ReactJS Redux.

## Back-End

Product information was stored in a PostgreSQL database. Express RESTful APIs were used to enter and retrieve data. Product images were stored in AWS S3.

## Deployment

The application was deployed on AWS Elastic Beanstalk. The PostrgresQL database was hosted on AWS RDS.

- This application is not currently deployed

## Requirements

- Node 6.13.0
- etc

# GetStarted

Take the following steps to run the app in your localhost, you will need to have the following:

- A PostgreSQL database must be set up, and the appropriate credentials must be added to the config.js file.

From terminal in the index folder:

Front-End (inside client directory):
```
npm install
npm start
npm run dev
```

Back-End (inside server directory):
```
npm install
npm start
npm run dev
```

# Reflections

## Challenges

"paperclips" was developed by a team of 7 engineers over a period of a week, based on a client's request. As the product manager, challenges revolved around team communication, task management, and product delivery.

## Learnings

Experience as the product manager was rewarding in that it taught me of the importance of a robust communication and ticketing system to ensure a collaborative environment. Communication was maintained through Slack, while a detailed ticketing system was implemented with Trello. Furthermore, scheduling meetings/presentations with the client, and stand-ups/retrospectives with the paperclips team was an opportunity to practice management and team organization. Balancing managerial responsibilities with assisting development in areas of need was beneficial in exercising time management and task prioritization.

## Contributors

- [Gabriel Anderson](https://github.com/Gabe-lee)
- [Benjamin Hong](https://github.com/bhong35)
- [Sam Lawson](https://github.com/samlawson355)
- [Matt Lucas](https://github.com/mlucas24)
- [David Silva](https://github.com/davidsilva2841)
- [Collin Snyder](https://github.com/Collin-Snyder)
- [Alyssa Wadley](https://github.com/arwadley)
