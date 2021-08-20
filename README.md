# Ipgeobase

Get metadata by IP address. 

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'ipgeobase'
```

And then execute:

    $ bundle install

Or install it yourself as:

    $ gem install ipgeobase

## Usage

```ruby
meta = Ipgeobase.lookup('9.9.9.9')
meta.country # United States
meta.countryCode # US
meta.city # Berkeley
meta.lat # 37.8767
meta.lon # -122.2676
```

## Development

After checking out the repo, run `bin/setup` to install dependencies. Then, run `rake test` to run the tests. You can also run `bin/console` for an interactive prompt that will allow you to experiment.

To install this gem onto your local machine, run `bundle exec rake install`. To release a new version, update the version number in `version.rb`, and then run `bundle exec rake release`, which will create a git tag for the version, push git commits and the created tag, and push the `.gem` file to [rubygems.org](https://rubygems.org).

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/[USERNAME]/ipgeobase.

## Workflow
![example workflow](https://github.com/marselgabdulov/ipgeobase/github/workflows/main.yml/badge.svg)
