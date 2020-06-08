# Monkey::Runner
This is an exploratory testing tool that implements **dumb monkey testing** approach. It performs random actions to your application to find major bugs that could crash your entire system.

The monkey is dumb, because:
- Has no knowledge about application or system
- Has no clue about valid or expected user behavior
- Makes no assumptions about system capabilities and flow of application

This tool requires no setup and could be used on any application. But finding any bug could take some time and reproducing it could be challenging.

Also could be useful for load and stress testing.

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'monkey-runner'
```

And then execute:

    $ bundle install

Or install it yourself as:

    $ gem install monkey-runner

## Usage

TODO: Write usage instructions here

## Development

After checking out the repo, run `bin/setup` to install dependencies. Then, run `rake test` to run the tests. You can also run `bin/console` for an interactive prompt that will allow you to experiment.

To install this gem onto your local machine, run `bundle exec rake install`. To release a new version, update the version number in `version.rb`, and then run `bundle exec rake release`, which will create a git tag for the version, push git commits and tags, and push the `.gem` file to [rubygems.org](https://rubygems.org).

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/[USERNAME]/monkey-runner. This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [code of conduct](https://github.com/[USERNAME]/monkey-runner/blob/master/CODE_OF_CONDUCT.md).


## License

The gem is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).

## Code of Conduct

Everyone interacting in the Monkey::Runner project's codebases, issue trackers, chat rooms and mailing lists is expected to follow the [code of conduct](https://github.com/[USERNAME]/monkey-runner/blob/master/CODE_OF_CONDUCT.md).
