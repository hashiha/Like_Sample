# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

gem 'devise'

$ bundle install

$ rails g devise:install

$ rails g devise user

$ rails g devise:views

$ rails g model post content:string user:references

$ rails db:migrate

$ rails g controller users index show

$ rails g controller posts index show

$ rails g model like post:references user:references

$ rails db:migrate

$ rails g controller likes

* ...
