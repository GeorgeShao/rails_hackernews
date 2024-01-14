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

## Rails Commands Used
```
rails new rails_hackernews

rails generate model User email:string username:string password:string
rails db:migrate

rails generate model Post link:string published:boolean
rails db:migrate

rails generate migration add_user_id_to_posts user_id:integer
rails db:migrate

rails generate model Comment text:string user_id:integer post_id:integer
rails db:migrate
```
