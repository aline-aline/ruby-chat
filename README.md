# RubyChat

RubyChat is an application like a Slack to send messages between groups.

## [Stack]
- Ruby on Rails
- Docker

## How to use it
* Clone this repository
* Run docker-composer build
* Run docker-compose run --rm app bundle exec rake db:create db:migrate
* Run docker-compose up
## Run tests
```
docker-compose exec app bundle exec spring rspec
```
