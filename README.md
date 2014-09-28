aut_system
==========

Example of gem Devise authentication system used for a Rails 4 applications.

####Devise setup
Add "gem 'devise'" to gemfile.

Run the following commands:
bundle install
rails generate devise:install
rails generate devise User
rake db:migrate

####Create default User from db/seeds:
rake db:seed
