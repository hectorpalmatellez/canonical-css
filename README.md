# CanonicalCss

Includes [Marxo's Canonical.css](https://github.com/marxo/Canonical.css) as a lightweight and modern alternative to [normalize-rails](https://github.com/markmcconachie/normalize-rails).

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'canonical_css'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install canonical_css

## Usage

After installing, go to `application.css` and add:

```css
*= require canonical

Of, to be more specific, you could add it in any `.scss` with:

```css
@import 'canonical';



## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/hectorpalmatellez/canonical-css. This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [Contributor Covenant](contributor-covenant.org) code of conduct.


## License

The gem is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).