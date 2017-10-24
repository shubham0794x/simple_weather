# README

This is Simple Weather app, weather data by [OpenWeatherMap API](http://openweathermap.org/).

# System dependencies

* Ruby 2.4.2
* Rails 5.1.4
* [direnv](https://direnv.net/)

# Setup

Run just `bin/setup` at project root directory.

# Configuration

Setup MasterData of City.

```
curl -L http://bulk.openweathermap.org/sample/city.list.min.json.gz | gunzip -c > db/masters/cities.json
```

* Database creation

(TODO)

* Database initialization

(TODO)

* How to run the test suite

(TODO)

* Services (job queues, cache servers, search engines, etc.)

(TODO)
