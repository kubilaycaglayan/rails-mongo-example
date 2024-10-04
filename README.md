# README

Source: https://www.mongodb.com/docs/mongoid/current/tutorials/getting-started-rails7/


rails new blog --skip-active-record
bin/rails g mongoid:config
bin/rails g scaffold Post title:string body:text
bin/rails g scaffold Comment name:string message:string post:belongs_to

