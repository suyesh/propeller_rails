# PropellerRails

Propeller Material Design Framework for Rails. It comes bundled with Bootstrap and Jquery. For Detailed documentation go to [propeller.in](http://propeller.in/)

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'propeller_rails'
```

## Usage

After adding ```propeller_rails``` to your Gemfile, run ```bundle install```. Then add codes below to your project.

### In app/assets/stylesheets

First Rename ```application.css``` to ```application.scss``` , then add ```@import 'propeller';```

### In app/assets/javascripts/application.js

Add ```//= require propeller```

## Development

After checking out the repo, run `bin/setup` to install dependencies. You can also run `bin/console` for an interactive prompt that will allow you to experiment.

To install this gem onto your local machine, run `bundle exec rake install`. To release a new version, update the version number in `version.rb`, and then run `bundle exec rake release`, which will create a git tag for the version, push git commits and tags, and push the `.gem` file to [rubygems.org](https://rubygems.org).

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/suyesh/propeller_rails.
