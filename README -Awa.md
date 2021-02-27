# Unit 18 PWA Homework: Online/Offline Budget Trackers
https://progressive-budget-awa.herokuapp.com/
Add functionality to our existing Budget Tracker application to allow for offline access and functionality.

The user will be able to add expenses and deposits to their budget with or without a connection. When entering transactions offline, they should populate the total when brought back online.

Offline Functionality:

  * App enters deposits offline on local host 3000

  * App enter expenses offline

When brought back online:

  * App adds Offline entries to a tracker.

## User Story
AS AN avid traveller
I WANT to be able to track my withdrawals and deposits with or without a data/internet connection
SO THAT my account balance is accurate when I am traveling

## Business Context

Gives users a fast and easy way to track their money is important, but allowing them to access that information anytime is even more important. Having offline functionality is paramount to our applications success.


## Acceptance Criteria
GIVEN a user is on Budget App without an internet connection
WHEN the user inputs a withdrawal or deposit
THEN that will be shown on the page, and added to their transaction history when their connection is back online.

  * Application tested on local host 3000 worked as required


* App Deployed with Heroku and MongoDB Atlas.](../04-Important/MongoAtlas-Deploy.md)

## Submission on BCS
*Heroku link
* https://progressive-budget-awa.herokuapp.com/
*Github repository link
https://github.com/francisawa/Progressive-Budget
