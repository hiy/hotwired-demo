# hotwired-demo

$ ruby -v
ruby 3.0.0p0 (2020-12-25 revision 95aff21468) [x86_64-darwin19]
$ rails -v
Rails 6.1.0

$ mkdir hotwired-demo
$ cd hotwired-demo
$ gem install rails --no-document
$ rails new . --skip-javascript

Gemfile

+ gem 'hotwire-rails'
+ gem ‘redis’

bundle

bin/rails hotwire:install 


bin/rails g scaffold room name:string
bin/rails db:migrate

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

* ...
