# Set

Welcome to your new gem! In this directory, you'll find the files you need to be able to package up your Ruby library into a gem. Put your Ruby code in the file `lib/set`. To experiment with that code, run `bin/console` for an interactive prompt.

TODO: Delete this and the text above, and describe your gem

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'set'
```

And then execute:

    $ bundle install

Or install it yourself as:

    $ gem install set

## Usage

```ruby
require 'set'
s1 = Set[1, 2]                        #=> #<Set: {1, 2}>
s2 = [1, 2].to_set                    #=> #<Set: {1, 2}>
s1 == s2                              #=> true
s1.add("foo")                         #=> #<Set: {1, 2, "foo"}>
s1.merge([2, 6])                      #=> #<Set: {1, 2, "foo", 6}>
s1.subset?(s2)                        #=> false
s2.subset?(s1)                        #=> true
```

## Development

After checking out the repo, run `bin/setup` to install dependencies. Then, run `rake test` to run the tests. You can also run `bin/console` for an interactive prompt that will allow you to experiment.

To install this gem onto your local machine, run `bundle exec rake install`. To release a new version, update the version number in `version.rb`, and then run `bundle exec rake release`, which will create a git tag for the version, push git commits and tags, and push the `.gem` file to [rubygems.org](https://rubygems.org).

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/ruby/set.

Feature requests should also go to https://bugs.ruby-lang.org/ for wider audience and discussion.
