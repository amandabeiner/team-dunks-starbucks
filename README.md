# Team Dunks vs. Starbucks

A live-coded clinic to practice using FactoryGirl in Rspec and Capybara tests.

The app allows a user to create add a member to a specific team. We want to test our User and Team models!

You should do the following:
* Create database tables for `users` and `teams`
* Create the correspoding models
* Create an index page to display the users, sorted by team
* Create a form to add a new user who belongs to a team

You should test the following:
* That the `User` model has the attributes we expect
* That the `Team` model has the attributes we expect
* That visiting the `index` page shows the information we expect
* That adding a team member behaves the way we expect

You should do the following for test support:
* Create a `User` factory
* Create a `Team` factory
* Use these factories when creating your tests!

## Setup
To get set up, run the following:
```no-highlight
  bundle
  rake db:create
  ruby app.rb
```

Then navigate to `localhost:4567`

You can run your tests by running `rake` in a new terminal tab.
