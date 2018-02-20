# README

Welcome to the React-Rails Boilerplate. 

Please read the following information tosetup the project on your local machine.

## Setup

Project Ruby Version: 2.5.0

Project Rails Version: 5.1.4

1. Git clone this repository

    Run: `git clone git@github.com:Rheisen/rails-react_boilerplate.git`

2. Navigate into the project folder and set up the database

    Run: `rake db:create`
    
    Run: `rake db:migrate`

3. Done!

## Running on Local Machine

If the project has been set up correctly running on local should be quick.

Install foreman on your local machine if you don't have it:

`gem install foreman` (make sure this is NOT added to the project Gemfile)

Start: `foreman start -f Procfile.dev -p 3000`

