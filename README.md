aut_system
==========

Authentication system for Rails 4 applications

bundle install

rails generate devise:install

rails generate devise User

rake db:migrate

rails c
->
User.create!({email: "example@email.com", :password => "12345678"})

OR

rake db:seed
