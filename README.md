# A1409yoHealth

[![Build Status](https://travis-ci.org/yuchan-edu/a1409yo_health.svg)](https://travis-ci.org/yuchan-edu/a1409yo_health)

Simple Health Calculator

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'a1409yo_health'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install a1409yo_health

## Usage

    require 'a1409yo_health'
    
    A1409yoHealth::BMI.exec(55,170)
    # => 19.031141868512112
    
## Contributing

1. Fork it ( https://github.com/[my-github-username]/a1409yo_health/fork )
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create a new Pull Request
