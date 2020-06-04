# Budget_Tracker
 Never a penny out of place

## What this project is
With this budget tracking application, the user will be able to add expenses and deposits to their budget with or without a connection. When entering transactions offline, the total should populate when brought back online.

Offline Functionality:

  * Enter deposits offline

  * Enter expenses offline

When brought back online:

  * Offline entries should be added to tracker.

## Demo
![demo](demo.gif)

## Why I began this project
Giving users a fast and easy way to track their money is important, but allowing them to access that information anytime is even more important. Having offline functionality is paramount to keeping track of funds in situations where an internet connection is not promised. Even while traveling in remote locations, you should always be aware of your accurate account balance.

## How I implemented this project
This project was implemented using [Node.js](https://nodejs.org/en/about/), [Express](https://expressjs.com/), [MongoDB](https://www.mongodb.com/) with [Mongoose](https://mongoosejs.com/docs/) dependency, and [Morgan](https://www.npmjs.com/package/morgan) logger middleware, with [Bootstrap](https://getbootstrap.com/) for the front-end and [Chart.js](https://www.chartjs.org/) for the pretty graphs.

## What I hope to eventually accomplish with this project
To more completely track expenses (even those that are offline) I would like to add categories, or tags, so that transactions of a similar type can be grouped together and sorted accordingly
