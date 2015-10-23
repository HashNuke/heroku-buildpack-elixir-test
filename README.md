# HerokuBuildpackTest

**TODO: Add description**

## Installation

If [available in Hex](https://hex.pm/docs/publish), the package can be installed as:

  1. Add heroku_buildpack_test to your list of dependencies in `mix.exs`:

        def deps do
          [{:heroku_buildpack_test, "~> 0.0.1"}]
        end

  2. Ensure heroku_buildpack_test is started before your application:

        def application do
          [applications: [:heroku_buildpack_test]]
        end
