# RubyChat

RubyChat is an application like a Slack to send messages between groups.
## Getting Started
### Prerequisites

This app is docker based. To avoid extra configurations, you should have `docker` and `docker-compose` installed. 

If you don't want to install these softwares, you will be able to use this app installing `ruby` (>= 2.3) and `Postgresql` (>= 9.5).
### Installing

* Clone this repo `git clone https://github.com/aline-aline/ruby-chat`;
  * In the repo folder, run: 
    * `docker-compose build`;
    * `docker-compose run --rm website rake db:create`;
    * `docker-compose run --rm website rake db:migrate`.
## Running the tests

```
docker-compose exec app bundle exec spring rspec
```
## Built With

* Ruby On Rails: http://rubyonrails.org/
* Docker: https://www.docker.com/
* Docker-Compose: https://docs.docker.com/compose/

## Contributing

Want to contribute? Fork and send a pull request. Have any questions? Open an issue or contact me.
## License

This project is licensed under the MIT License.


