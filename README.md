aut_system
==========

Example of gem Devise authentication system used for a Rails 4 application.

####Devise setup
Add "gem 'devise'" to gemfile.

Run the following commands:
1. bundle install    
2. rails generate devise:install  
3. rails generate devise User  
4. rake db:migrate  

####Create default User from db/seeds
5. rake db:seed
