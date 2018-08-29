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

To run
---
``` sh
# run
docker-compose up

# down
docker-compose down

# migrate
docker-compose run --rm app rake db:create
```
