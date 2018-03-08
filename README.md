# SLLA

A simple protest calendar for the Los Angeles area. [Visit the site here.](http://stayloudla.com/)
Want to contribute? We meet every Wednesday night! Ask for an invitation in the Hack For LA Slack channel.

## Setting Up For Local Development
1. If you don't have Ruby already installed (IE you are not on a mac), install Ruby 2.4
1. Install Rails 5.1.4+
1. Fork the repo
1. Clone your forked repo

    `git clone https://github.com/<YOUR USERNAME>/SLLA.git`

1. Navigate to the SLLA folder

    `cd SLLA`

1. Add a new upstream remote to the original repo

    `git remote add upstream https://github.com/seport/SLLA.git`
    
1. Checkout the `rails` branch

    `git checkout --track origin/rails`
    
1. Run `bundle install`
1. Run the migrations.
    
    `rake db:migrate`

1. Run your server.

    `bin/rails server`

1. Navigate to `localhost:3000` in your browser. You should see the homepage!

## Pulling From This Repository
1. When you need to pull code from this repository, do it like this!

    `git fetch upstream`
    
    `git merge upstream/<BRANCH NAME>`
