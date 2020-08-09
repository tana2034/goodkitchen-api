# README

* Ruby version
2.6.5

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* Local environment

```
docker-compose build 
# create local db
docker-compose run api bundle exec rails db:create
docker-compose run api bundle exec rails db:migrate
# rails server
docker-compose up -d
# see localhost:3000
```

