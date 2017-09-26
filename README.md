# NiceCommit

This gem install a git hook into your local repository with one of the code Linters you choose according to your language: java, javascript or swift.
  

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'niceCommit'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install niceCommit

## Usage

In the root directory of your project run:
```
niceCommit LINTER
``` 
where LINTER is one of the following:
- checkStyle    for java/android.
- swiftLint     for Swift.
- eslint        for Javascript.


## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/sanchezcr/niceCommit. This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [Contributor Covenant](http://contributor-covenant.org) code of conduct.

## License

The gem is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).

## Code of Conduct

Everyone interacting in the NiceCommit project’s codebases, issue trackers, chat rooms and mailing lists is expected to follow the [code of conduct](https://github.com/[USERNAME]/niceCommit/blob/master/CODE_OF_CONDUCT.md).
