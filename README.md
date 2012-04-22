# Ruby on Rails Tutorial: sample application

This is the sample application for
[*Ruby on Rails Tutorial: Learn Rails by Example*](http://railstutorial.org)
by [Michael Hartl](http://michaelhartl.com/).

# How to set up PostgreSQL

1. Make sure gem 'pg' is in the Gemfile.
2. Make sure config/database.yml is talking about postgresql, and make a note of
   the user name (sample\_app) here. This will be done by default if you create
   the project with 'rails new sample\_app --database=postgresql'
3. Open PostgreSQL by running 'sudo -u postgres psql'
4. Run 'CREATE ROLE sample\_app CREATEDB LOGIN'
5. Run 'rake db:create:all'
6. Run 'rake db:migrate'
