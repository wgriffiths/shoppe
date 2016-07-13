# Shoppe

Shoppe is an Rails-based e-commerce platform which allows you to easily introduce a
catalogue-based store into your Rails 4 applications. 

**Shoppe is currently unsupported and unmaintained. Please see [Shopr](https://github.com/shoprgem/shopr), a fork of Shoppe**

[![Build Status](https://travis-ci.org/tryshoppe/shoppe.svg?branch=master)](https://travis-ci.org/tryshoppe/shoppe)
![GemVersion](https://badge.fury.io/rb/shoppe.png)
[![Code Climate](https://codeclimate.com/github/tryshoppe/core/badges/gpa.svg)](https://codeclimate.com/github/tryshoppe/core)

* [Check out the website](http://tryshoppe.com)
* [View the demo site](http://demo.tryshoppe.com)
* [Read the Getting Started guide](http://tryshoppe.com/docs/tutorials/getting-started)
* [Check out the demo site source](http://github.com/tryshoppe/example-store)
* [Read the release notes](https://github.com/tryshoppe/core/blob/master/CHANGELOG.md)
* [Read API documentation](http://api.tryshoppe.com)

## Is it any good?

[Yes](http://news.ycombinator.com/item?id=3067434)

## Features

* An attractive & easy to use admin interface with integrated authentication
* Full product/catalogue management
* Stock control
* Tax management
* Flexible & customisable order flow
* Delivery/shipping control, management & weight-based calculation

## Getting Started

Shoppe provides the core framework for the store and you're responsible for creating
the storefront which your customers will use to purchase products. In addition to
creating the UI for the frontend, you are also responsible for integrating with whatever
payment gateway takes your fancy.

### Installing into a new Rails application

To get up and running with Shoppe in a new Rails application is simple. Just follow the
instructions below and you'll be up and running in minutes.

    rails new my_store
    cd my_store
    echo "gem 'shoppe'" >> Gemfile
    bundle
    rails generate shopr:setup
    rails generate nifty:key_value_store:migration
    rake db:migrate shopr:setup
    rails server

## Contribution

If you'd like to help with this project, please get in touch with me. The best place is on
Twitter (@adamcooke) or by e-mail to adam@atechmedia.com.

## License

Shoppe is licenced under the MIT license. Full details can be found in the MIT-LICENSE
file in the root of the repository.
