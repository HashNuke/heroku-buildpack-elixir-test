# HerokuBuildpackTest

Sample app to test with the [Heroku Elixir Buildpack](http://github.com/HashNuke/heroku-buildpack-elixir)

## Usage

To create an app run the following commands:

```
$ git clone https://github.com/HashNuke/heroku-buildpack-elixir-test.git
$ cd heroku-buildpack-elixir-test
$ heroku create --buildpack "https://github.com/HashNuke/heroku-buildpack-elixir.git"
$ git push heroku master
```
