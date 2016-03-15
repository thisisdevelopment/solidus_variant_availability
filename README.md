SolidusVariantAvailability
==========================

[![Build Status](https://travis-ci.org/madetech/solidus_variant_availability.svg?branch=master)](https://travis-ci.org/madetech/solidus_variant_availability)

Add variant based availability to `Spree::Variant`

Installation
------------

Add solidus_variant_availability to your Gemfile:

```ruby
gem 'solidus_variant_availability'
```

Bundle your dependencies and run the installation generator:

```shell
bundle
bundle exec rails g solidus_variant_availability:install
```

Testing
-------

First bundle your dependencies, then run `rake`. `rake` will default to building the dummy app if it does not exist, then it will run specs, and [Rubocop](https://github.com/bbatsov/rubocop) static code analysis. The dummy app can be regenerated by using `rake test_app`.

```shell
bundle
bundle exec rake
```

When testing your applications integration with this extension you may use it's factories.
Simply add this require statement to your spec_helper:

```ruby
require 'solidus_variant_availability/factories'
```

Copyright (c) 2016 [name of extension creator], released under the New BSD License