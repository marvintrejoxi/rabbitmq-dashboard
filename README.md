# README

## Rabbitmq-dashboard

* Ruby version `2.5.1` and Rails version `2.5.1`

* Run `bundle install`

* Run `rails db:setup` for create database

* In a terminal run the next task rake:
```ruby
  WORKERS=PostsWorker rake sneakers:run
```

* In another terminal lift the redis service with the command: `redis-server`

* Run `rails s -p 3001` and go to `http://localhost:3001`

* In `rabbit-blog` app create a post and then refresh the `http://localhost:3001` url and you will see the information created in `rabbit-blog` by means of `rabbitmq-server` and `redis`

## Documentation

* `https://www.monterail.com/blog/2014/event-sourcing-on-rails-with-rabbitmq`