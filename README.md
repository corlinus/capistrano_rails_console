# Capistrano Rails Console [![Build Status](https://travis-ci.org/timoschilling/capistrano_rails_console.png?branch=master)](https://travis-ci.org/timoschilling/capistrano_rails_console)

Open a rails console the first app server.

## Installation

Add this line to your application's Gemfile:

    gem 'capistrano_rails_console'

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install capistrano_rails_console

Require it in your Capfile or deploy.rb:

    require "capistrano_rails_console/recipes"

## Usage

    $ cap rails:console

## Todo / Roadmap

* use Capistrano API to run command, not build it by hand

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request
